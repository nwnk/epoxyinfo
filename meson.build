project(
    'epoxyinfo',
    'c',
    license: 'MIT',
)

cc = meson.get_compiler('c')

srcs = [
    'epoxyinfo.c',
    'glinfo_common.c',
]

executable(
    'epoxyinfo',
    srcs,
    dependencies: [
        dependency('epoxy'),
        dependency('x11'),
    ],
    install: true
)
