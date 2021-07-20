vars = {
  # Common settings.
  "project_directory" : "gclient_repo_1",
}


hooks = [
  {
    'name': 'submodule',
    'pattern': '.',
    'action': [
        'git',
        '--git-dir=Var("project_directory")/.git',
        'submodule init',
        '&&',
        'git',
        '--git-dir=Var("project_directory")/.git',
        'submodule update'
    ]
  }
]