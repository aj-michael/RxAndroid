android_binary(
    name = "app",
    manifest = "src/main/AndroidManifest.xml",
    custom_package = "rx.android.samples",
    srcs = glob(["src/main/java/**/*.java"]),
    resource_files = glob(["src/main/res/**"]),
    deps = [
        "@rxandroid//aar",
        "@rxjava//jar",
    ],
)
