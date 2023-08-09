exodus_sources = [
  'main.c',
  'exodus-application.c',
  'exodus-window.c',
]

exodus_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1', version: '>= 1.2'),
]

exodus_sources += gnome.compile_resources('exodus-resources',
  'exodus.gresource.xml',
  c_name: 'exodus'
)

executable('exodus', exodus_sources,
  dependencies: exodus_deps,
       install: true,
)
