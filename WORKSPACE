workspace(name="org_dnosproject_dnos_services")

git_repository(
    name = "dnos_core",
    remote = "https://github.com/dnos-project/dnos-core.git",
    commit = "9618f0619f37ccbee81afdcc3ec8a17c6f35d36b"

)

load("@dnos_core//tools/build/bazel:generate_workspace.bzl", "generated_maven_jars")

generated_maven_jars()