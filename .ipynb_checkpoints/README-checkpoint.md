# mcrnn-text
A Python program to recognize text lines from old and grainy documents

## To safely upload

Install homebrew (follow prompts):
```python
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install git-lfs:
```python
brew install git-lfs
```

Update git:
```python
git install lfs
```

Track .pth files:
```python
git lfs track "*.pth"
```

Add all changes:
```python
git add .
```

Verify only pth files are added to LFS:
```python
git lfs ls-files
```

Commit and push!