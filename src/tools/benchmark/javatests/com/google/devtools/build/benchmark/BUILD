package(default_visibility = ["//src/tools/benchmark:__subpackages__"])

java_test(
    name = "BazelBuildCaseTest",
    srcs = ["BazelBuildCaseTest.java"],
    deps = [
        "//src/tools/benchmark/java/com/google/devtools/build/benchmark:benchmark_lib",
        "//src/tools/benchmark/java/com/google/devtools/build/benchmark:build_data_proto",
        "//third_party:guava",
        "//third_party:junit4",
        "//third_party:truth",
    ],
)

java_test(
    name = "BazelBuilderTest",
    srcs = ["BazelBuilderTest.java"],
    deps = [
        "//src/main/java/com/google/devtools/build/lib:shell",
        "//src/tools/benchmark/java/com/google/devtools/build/benchmark:benchmark_lib",
        "//src/tools/benchmark/java/com/google/devtools/build/benchmark:build_data_proto",
        "//third_party:guava",
        "//third_party:junit4",
        "//third_party:truth",
    ],
)

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
)
