package(default_visibility = ["//visibility:public"])

proto_library(
    name = "annotations_proto",
    srcs = [
        "annotations.proto",
    ],
    deps = [
        "//trpc/api:http_proto",
        "@com_google_protobuf//:descriptor_proto",
    ],
)

proto_library(
    name = "http_proto",
    srcs = [
        "http.proto",
        "openapiv2.proto",
    ],
)
