# MangaTools

MangaTools is a cli tool to help you organize your digital manga

<img float="left" src="logo.png" alt="" width="80"/>

## Features

* Search manga details and covers
* Organize volume pages to chapters
* Archive chapters to .cbz files.

## Installation


```sh
1. git clone https://github.com/arrow420/manga-tools.git
2. cd mangatools
3. pip install .
4. mangatools [command]
```

## Usage
Below is a list of the currently support API command you can run.

* [`mangatools search <TITLE>`](#search) - Search details about manga from Mangadex.
* [`mangatools extract`](#extract)       - Extract pages from volumes and organize them to chapters.
* [`mangatools archive`](#archive)       - Archive chapters into .cbz files.


### Search
The search command uses mangadex to fetch details about manga and creates a details.json file for Tachiyomi.


```commandline
Usage: mangatools search [OPTIONS] TITLE

Options:
  --doujin      Shows manga with the doujin tag
  --no-covers   Doesn't download manga volume coverart
  --no-details  Doesn't create a details.json file
  --help        Show this message and exit.
```


### Extract
Blalawdwodjawdj owadojwalkndw kwdknkwajdkwajdjwalk  djlkwa manga ojdwjod ojwdojwdojwojowdwdwkndadanwdnawkdnwakn dkwakndwank wefeefe.


```commandline
Usage: mangatools extract [OPTIONS]

Options:
  --help  Show this message and exit.
```


### Archive
The archive command uses 7-zip to archive chapter folders into .cbz archives.


```commandline
Usage: mangatools archive [OPTIONS]

Options:
  --help  Show this message and exit.
```


## Contact

If you want to contact me you can reach me at <arrowsoftwaresolutions@gmail.com>.

## License
<!--- If you're not sure which open license to use see https://choosealicense.com/--->

This project uses the following license: [MIT](<https://choosealicense.com/licenses/mit/>).

Copyright (c) 2021 Arrow

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
