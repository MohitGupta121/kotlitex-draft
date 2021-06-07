load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# Add support for Kotlin: https://github.com/bazelbuild/rules_kotlin.
rules_kotlin_version = "v1.5.0-alpha-2"
rules_kotlin_sha = "6194a864280e1989b6d8118a4aee03bb50edeeae4076e5bc30eef8a98dcd4f07"
http_archive(
    name = "io_bazel_rules_kotlin",
    sha256 = rules_kotlin_sha,
    urls = ["https://github.com/bazelbuild/rules_kotlin/releases/download/%s/rules_kotlin_release.tgz" % rules_kotlin_version],
)

android_sdk_repository(
  name = "androidsdk",
  api_level = 28,
)
