cc_library(
    name = "benchmark",
    srcs = [
        "src/arraysize.h",
        "src/benchmark.cc",
        "src/check.h",
        "src/colorprint.cc",
        "src/colorprint.h",
        "src/commandlineflags.cc",
        "src/commandlineflags.h",
        "src/complexity.cc",
        "src/complexity.h",
        "src/console_reporter.cc",
        "src/csv_reporter.cc",
        "src/cycleclock.h",
        "src/internal_macros.h",
        "src/json_reporter.cc",
        "src/log.cc",
        "src/log.h",
        "src/mutex.h",
        "src/reporter.cc",
        "src/re.h",
        "src/re_posix.cc",
        "src/re_std.cc",
        "src/sleep.cc",
        "src/sleep.h",
        "src/stat.h",
        "src/string_util.cc",
        "src/string_util.h",
        "src/sysinfo.cc",
        "src/sysinfo.h",
        "src/walltime.cc",
        "src/walltime.h",
    ],
    hdrs = [
        "include/benchmark/benchmark.h",
        "include/benchmark/benchmark_api.h",
        "include/benchmark/macros.h",
        "include/benchmark/reporter.h",
    ],
    visibility = ["//test:__pkg__"],
    defines = ["HAVE_STD_REGEX"],
    includes = ["include"],
    linkopts = ["-pthread"],
)