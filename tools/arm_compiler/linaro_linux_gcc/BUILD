package(default_visibility = ['//tools/arm_compiler:__pkg__'])

filegroup(
  name = 'gcc',
  srcs = [
    '@linaro_linux_gcc_repo//:gcc',
    'arm-linux-gnueabihf-gcc',
  ],
)

filegroup(
  name = 'ar',
  srcs = [
    '@linaro_linux_gcc_repo//:ar',
    'arm-linux-gnueabihf-ar',
  ],
)

filegroup(
  name = 'ld',
  srcs = [
    '@linaro_linux_gcc_repo//:ld',
    'arm-linux-gnueabihf-ld',
  ],
)

filegroup(
  name = 'nm',
  srcs = [
    '@linaro_linux_gcc_repo//:nm',
    'arm-linux-gnueabihf-nm',
  ],
)

filegroup(
  name = 'objcopy',
  srcs = [
    '@linaro_linux_gcc_repo//:objcopy',
    'arm-linux-gnueabihf-objcopy',
  ],
)

filegroup(
  name = 'objdump',
  srcs = [
    '@linaro_linux_gcc_repo//:objdump',
    'arm-linux-gnueabihf-objdump',
  ],
)

filegroup(
  name = 'strip',
  srcs = [
    '@linaro_linux_gcc_repo//:strip',
    'arm-linux-gnueabihf-strip',
  ],
)

filegroup(
  name = 'as',
  srcs = [
    '@linaro_linux_gcc_repo//:as',
    'arm-linux-gnueabihf-as',
  ],
)

filegroup(
  name = 'clang',
  srcs = [
    'clang_bin/clang',
  ],
)

filegroup(
  name = 'clang-ld',
  srcs = [
    'clang_bin/ld',
    ':ld',
  ],
)

filegroup(
  name = 'tool-wrappers',
  srcs = [
    ':gcc',
    ':ar',
    ':ld',
    ':nm',
    ':objcopy',
    ':objdump',
    ':strip',
    ':as',
    'clang_bin/as',
    ':clang',
    ':clang-ld',
  ],
)

filegroup(
  name = 'clang-symlinks',
  srcs = glob([
    'clang_more_libs/**',
    'clang_syroot/**',
  ]),
)