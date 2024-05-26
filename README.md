# PINGU
Line stickers downloader

<div align="center">
	<img src="https://github.com/Sylux6/pingu/blob/main/doc/pingu.gif?raw=true" alt="pingu">
</div>

## Usage

### Method 1 (recommended)

1. Fork this repository
2. Go to [Github Actions](https://github.com/Sylux6/pingu/actions/workflows/pingu.yml) in your forked repository
3. Run Pingu workflow
4. Download stickers.zip artifact

### Method 2

1. Install ffmpeg and add to your PATH
2. Install the requirements
3. Run main.py with Line url

```
pip install -r requirements.txt
python main.py <URL>
```

Stickers will be downloaded in the `stickers` folder
