# Welcome to my paper template

Should work for PRD.

To compile do
```shell
make
```

To generate tar file for arxiv do:
```shell
./make-submission.sh
```

To make a private copy of this repo:
```
# Create a bare clone of the repository.
git clone --bare git@github.com:vijayvarma392/paper_template.git
cd paper_template.git

# Create a new private repository on your Github page, in the usual way. Let
# this be called private_repo_name
git push --mirror git@github.com:<username>/private_repo_name.git

# Get rid of the bare repo
cd --
rm -rf paper_template.git

# Get your private repo in the usual way
git clone git@github.com:<username>/private_repo_name.git
```

Credits: Thanks to [Leo Stein](https://duetosymmetry.com/) for providing the
arxiv submission script.
