icon_sizes = ['16', '24', '32', '48', '64']

foreach i : icon_sizes
    install_data(
        join_paths(i, meson.project_name() + '.svg'),
        install_dir: join_paths(get_option('datadir'), 'icons', 'hicolor', i + 'x' + i, 'apps')
    )
endforeach