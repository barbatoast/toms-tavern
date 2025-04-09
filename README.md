# toms-tavern

Example Godot Game

## Git Large File Storage (LFS)

Git Large File Storage (LFS) replaces large files such as audio samples, videos, datasets, and graphics with text pointers inside Git, while storing the file contents on a remote server like GitHub.com or GitHub Enterprise.

### Configure Git LFS for Large Assets

```bash
brew install git-lfs
git lfs track "*.png"
git lfs track "*.wav"
```
