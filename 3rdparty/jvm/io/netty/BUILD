# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "netty_buffer",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":netty_common",
        "//external:jar/io/netty/netty_buffer",
    ],
)

java_library(
    name = "netty_codec",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":netty_buffer",
        ":netty_common",
        ":netty_transport",
        "//external:jar/io/netty/netty_codec",
    ],
)

java_library(
    name = "netty_codec_http",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":netty_buffer",
        ":netty_codec",
        ":netty_common",
        ":netty_transport",
        "//external:jar/io/netty/netty_codec_http",
    ],
)

java_library(
    name = "netty_codec_http2",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":netty_buffer",
        ":netty_codec",
        ":netty_codec_http",
        ":netty_common",
        ":netty_handler",
        ":netty_transport",
        "//external:jar/io/netty/netty_codec_http2",
    ],
)

java_library(
    name = "netty_codec_socks",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":netty_buffer",
        ":netty_codec",
        ":netty_common",
        ":netty_transport",
        "//external:jar/io/netty/netty_codec_socks",
    ],
)

java_library(
    name = "netty_common",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/io/netty/netty_common",
    ],
)

java_library(
    name = "netty_handler",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":netty_buffer",
        ":netty_codec",
        ":netty_common",
        ":netty_transport",
        "//external:jar/io/netty/netty_handler",
    ],
)

java_library(
    name = "netty_handler_proxy",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":netty_buffer",
        ":netty_codec",
        ":netty_codec_http",
        ":netty_codec_socks",
        ":netty_common",
        ":netty_transport",
        "//external:jar/io/netty/netty_handler_proxy",
    ],
)

java_library(
    name = "netty_resolver",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":netty_common",
        "//external:jar/io/netty/netty_resolver",
    ],
)

java_library(
    name = "netty_tcnative_boringssl_static",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/io/netty/netty_tcnative_boringssl_static",
    ],
)

java_library(
    name = "netty_transport",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":netty_buffer",
        ":netty_common",
        ":netty_resolver",
        "//external:jar/io/netty/netty_transport",
    ],
)
