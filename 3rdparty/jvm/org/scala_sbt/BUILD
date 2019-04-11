# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "actions",
    jars = [
        "//external:jar/org/scala_sbt/actions_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":compiler_interface",
        ":completion",
        ":io",
        ":librarymanagement_core",
        ":run",
        ":task_system",
        ":tasks",
        ":testing",
        ":util_logging",
        ":util_relation",
        ":util_tracking",
        ":zinc",
        ":zinc_apiinfo",
        ":zinc_classpath",
        ":zinc_ivy_integration",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_scalajson",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "collections",
    jars = [
        "//external:jar/org/scala_sbt/collections_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":util_position",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_scalajson",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "command",
    jars = [
        "//external:jar/org/scala_sbt/command_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":compiler_interface",
        ":completion",
        ":io",
        ":launcher_interface",
        ":librarymanagement_core",
        ":protocol",
        ":template_resolver",
        ":util_logging",
        ":zinc_classpath",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_core",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_scalajson",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

java_library(
    name = "compiler_interface",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":util_interface",
        "//external:jar/org/scala_sbt/compiler_interface",
    ],
)

scala_import(
    name = "completion",
    jars = [
        "//external:jar/org/scala_sbt/completion_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":collections",
        ":io",
        ":util_control",
        "//3rdparty/jvm/jline",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "core_macros",
    jars = [
        "//external:jar/org/scala_sbt/core_macros_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":collections",
        "//3rdparty/jvm/org/scala_lang:scala_compiler",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "io",
    jars = [
        "//external:jar/org/scala_sbt/io_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/com/swoval:apple_file_events",
        "//3rdparty/jvm/net/java/dev/jna",
        "//3rdparty/jvm/net/java/dev/jna:jna_platform",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

java_library(
    name = "launcher_interface",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/scala_sbt/launcher_interface",
    ],
)

scala_import(
    name = "librarymanagement_core",
    jars = [
        "//external:jar/org/scala_sbt/librarymanagement_core_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":io",
        ":launcher_interface",
        ":util_cache",
        ":util_logging",
        ":util_position",
        "//3rdparty/jvm/com/eed3si9n:gigahorse_okhttp",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_core",
        "//3rdparty/jvm/com/jcraft:jsch",
        "//3rdparty/jvm/com/squareup/okhttp3:okhttp_urlconnection",
        "//3rdparty/jvm/org/scala_lang:scala_compiler",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang:scala_reflect",
        "//3rdparty/jvm/org/scala_lang/modules:scala_xml",
    ],
)

scala_import(
    name = "librarymanagement_ivy",
    jars = [
        "//external:jar/org/scala_sbt/librarymanagement_ivy_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":librarymanagement_core",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_core",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_sbt/ivy",
    ],
)

scala_import(
    name = "logic",
    jars = [
        "//external:jar/org/scala_sbt/logic_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":collections",
        ":util_relation",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "main",
    jars = [
        "//external:jar/org/scala_sbt/main_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":actions",
        ":collections",
        ":command",
        ":compiler_interface",
        ":io",
        ":launcher_interface",
        ":librarymanagement_core",
        ":librarymanagement_ivy",
        ":logic",
        ":main_settings",
        ":run",
        ":util_logging",
        ":zinc_compile",
        "//3rdparty/jvm/com/github/cb372:scalacache_caffeine",
        "//3rdparty/jvm/org/apache/logging/log4j:log4j_api",
        "//3rdparty/jvm/org/apache/logging/log4j:log4j_core",
        "//3rdparty/jvm/org/apache/logging/log4j:log4j_slf4j_impl",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang/modules:scala_xml",
    ],
)

scala_import(
    name = "main_settings",
    jars = [
        "//external:jar/org/scala_sbt/main_settings_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":command",
        ":compiler_interface",
        ":completion",
        ":core_macros",
        ":io",
        ":librarymanagement_core",
        ":task_system",
        ":util_cache",
        ":util_logging",
        ":util_relation",
        ":zinc_classpath",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "protocol",
    jars = [
        "//external:jar/org/scala_sbt/protocol_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":collections",
        ":util_logging",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_core",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_scalajson",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_sbt/ipcsocket",
    ],
)

scala_import(
    name = "run",
    jars = [
        "//external:jar/org/scala_sbt/run_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":collections",
        ":io",
        ":util_logging",
        ":zinc_classpath",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "sbinary",
    jars = [
        "//external:jar/org/scala_sbt/sbinary_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang/modules:scala_xml",
    ],
)

java_library(
    name = "sbt",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":main",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//external:jar/org/scala_sbt/sbt",
    ],
)

scala_import(
    name = "task_system",
    jars = [
        "//external:jar/org/scala_sbt/task_system_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":collections",
        ":io",
        ":tasks",
        ":util_cache",
        ":util_logging",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "tasks",
    jars = [
        "//external:jar/org/scala_sbt/tasks_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":collections",
        ":util_control",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

java_library(
    name = "template_resolver",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/scala_sbt/template_resolver",
    ],
)

java_library(
    name = "test_agent",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":test_interface",
        "//external:jar/org/scala_sbt/test_agent",
    ],
)

java_library(
    name = "test_interface",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/scala_sbt/test_interface",
    ],
)

scala_import(
    name = "testing",
    jars = [
        "//external:jar/org/scala_sbt/testing_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":io",
        ":launcher_interface",
        ":test_agent",
        ":test_interface",
        ":util_logging",
        ":zinc_classpath",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_core",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_scalajson",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "util_cache",
    jars = [
        "//external:jar/org/scala_sbt/util_cache_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":io",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_murmurhash",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_scalajson",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang:scala_reflect",
    ],
)

scala_import(
    name = "util_control",
    jars = [
        "//external:jar/org/scala_sbt/util_control_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

java_library(
    name = "util_interface",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/scala_sbt/util_interface",
    ],
)

scala_import(
    name = "util_logging",
    jars = [
        "//external:jar/org/scala_sbt/util_logging_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":util_interface",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_core",
        "//3rdparty/jvm/com/eed3si9n:sjson_new_scalajson",
        "//3rdparty/jvm/com/lmax:disruptor",
        "//3rdparty/jvm/jline",
        "//3rdparty/jvm/org/apache/logging/log4j:log4j_api",
        "//3rdparty/jvm/org/apache/logging/log4j:log4j_core",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang:scala_reflect",
    ],
)

scala_import(
    name = "util_position",
    jars = [
        "//external:jar/org/scala_sbt/util_position_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "util_relation",
    jars = [
        "//external:jar/org/scala_sbt/util_relation_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "util_tracking",
    jars = [
        "//external:jar/org/scala_sbt/util_tracking_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":io",
        ":util_cache",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "zinc",
    jars = [
        "//external:jar/org/scala_sbt/zinc_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":zinc_classfile",
        ":zinc_compile_core",
        ":zinc_core",
        ":zinc_ivy_integration",
        ":zinc_persist",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "zinc_apiinfo",
    jars = [
        "//external:jar/org/scala_sbt/zinc_apiinfo_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":compiler_interface",
        ":zinc_classfile",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "zinc_classfile",
    jars = [
        "//external:jar/org/scala_sbt/zinc_classfile_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":compiler_interface",
        ":io",
        ":util_logging",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "zinc_classpath",
    jars = [
        "//external:jar/org/scala_sbt/zinc_classpath_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":compiler_interface",
        ":io",
        ":launcher_interface",
        "//3rdparty/jvm/org/scala_lang:scala_compiler",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "zinc_compile",
    jars = [
        "//external:jar/org/scala_sbt/zinc_compile_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":util_tracking",
        ":zinc_compile_core",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "zinc_compile_core",
    jars = [
        "//external:jar/org/scala_sbt/zinc_compile_core_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":compiler_interface",
        ":io",
        ":launcher_interface",
        ":util_control",
        ":util_logging",
        ":zinc_apiinfo",
        ":zinc_classfile",
        ":zinc_classpath",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang/modules:scala_parser_combinators",
    ],
)

scala_import(
    name = "zinc_core",
    jars = [
        "//external:jar/org/scala_sbt/zinc_core_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":compiler_interface",
        ":io",
        ":util_logging",
        ":util_relation",
        ":zinc_apiinfo",
        ":zinc_classpath",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "zinc_ivy_integration",
    jars = [
        "//external:jar/org/scala_sbt/zinc_ivy_integration_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":librarymanagement_core",
        ":zinc_compile_core",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "zinc_persist",
    jars = [
        "//external:jar/org/scala_sbt/zinc_persist_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":sbinary",
        ":zinc_core",
        "//3rdparty/jvm/com/trueaccord/scalapb:scalapb_runtime_2_12",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)
