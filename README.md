# Jupyter Notebook-based Hex Viewer

Barebones hex viewer based on Jupyter Notebooks, because I also value my retinas, all my devices are perma-locked on dark mode, and I mostly work with Python anyway.

Intended for a different kind of data mining - video game data. But I guess hex viewers have other uses...

## Notes

Imitates the output of HxD by default
![image](https://user-images.githubusercontent.com/1752285/226125688-52abea24-b5be-46cf-ba5c-ccaa5c85612f.png)


## Disclaimer

I might get some terminology wrong.

## Todo

- [x] Display hex data
- [x] Limit number of rows shown
- [ ] Start reading from offset (technically works, but not if you're reading near the end of the file)
- [x] Display offset column
- [ ] Display offset row
- [ ] Display decoded column
- [ ] Highlight differences between two files
- [ ] Gray out zeros

Would be nice:
- [ ] Interactive data inspector (ipywidgets?)
- [ ] Highlight data based on [ksy file](https://kaitai.io/)
