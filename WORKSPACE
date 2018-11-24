workspace(name = "cppast")

git_repository(
    name = "com_github_zaucy_type_safe",
    commit = "451a29fd9c4891eed6e7a72fa7e8069114498e74",
    remote = "https://github.com/zaucy/type_safe",
)

git_repository(
    name = "com_github_zaucy_debug_assert",
    commit = "4f2a8b69f8bd3fb5a5c0e57c2d9cb8849cf8c674",
    remote = "https://github.com/zaucy/debug_assert",
)

http_file(
    name = "catch2_hpp",
    url = "https://github.com/catchorg/Catch2/releases/download/v2.4.2/catch.hpp",
)

git_repository(
    name = "bazelregistry_tiny_process_library",
    commit = "8c8020a8709c27f754a4bfd323a470f86a6a96fe",
    remote = "https://github.com/bazelregistry/tiny-process-library",
)

git_repository(
    name = "bazelregistry_llvm",
    commit = "9c553d139158dd0aeb0e3b8ea0fa6544d5d2282e",
    remote = "https://github.com/bazelregistry/llvm",
)

load("@bazelregistry_llvm//:llvm.bzl", "llvm")
llvm()
