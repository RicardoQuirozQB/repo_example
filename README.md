# repo_example

To install the subpackage using token (recommended for avoiding password prompt):

1. Create [Personal Token](https://github.com/settings/tokens) (classic).  
  token: ghp_.....

2. Install package
```sh
pip install git+https://<token>@github.com/RicardoQuirozQB/repo_example.git@main#subdirectory=folder1/pckg
```


3. Test package:
```sh
  ❯ python -c "from so_ds_utils.module1 import func1; func1()"
  1
```