new_git_repository(
    name = "cppzmq",
    remote = "https://github.com/zeromq/cppzmq.git",
    commit = "c5611d6aff61515978330ae780379dcd4c15b3cd",
    build_file_content = """
cc_library(
	name = "cppzmq",
	hdrs = ["zmq.hpp"],
	visibility = ["//visibility:public"]
)""",
)

new_git_repository(
    name = "libzmq",
    remote = "https://github.com/zeromq/zeromq4-1.git",
    tag = "v4.1.5",
    build_file = "BUILD.libzmq"
)
