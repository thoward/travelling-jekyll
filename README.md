# travelling-jekyll

Jekyll, packaged with Traveling Ruby.

This project contains standalone executables for Jekyll 3.2.0, running on a bundled version of Ruby 2.1.5 provided by the [Traveling Ruby](http://phusion.github.io/traveling-ruby/) project. Platforms supported are OSX and Linux x86/x86_64.

## How to Use

1. Download the release tarball that is correct for your platform:
    * OSX: [jekyll-3.2.0-osx.tgz](https://github.com/thoward/travelling-jekyll/releases/download/1.0/jekyll-3.2.0-osx.tgz)
    * Linux x86: [jekyll-3.2.0-linux-x86.tgz](https://github.com/thoward/travelling-jekyll/releases/download/1.0/jekyll-3.2.0-linux-x86.tgz)
    * Linux x86_64: [jekyll-3.2.0-linux-x86_64.tgz](https://github.com/thoward/travelling-jekyll/releases/download/1.0/jekyll-3.2.0-linux-x86_64.tgz)
   
    *Example: Downloading the OSX version*

    ```shell
    $ wget https://github.com/thoward/travelling-jekyll/releases/download/1.0/jekyll-3.2.0-osx.tgz
    ```
2. Extract the tarball: 

    *Example: Extracting the OSX version*

    ```shell
    $ tar zxvf jekyll-3.2.0-osx.tgz
    ```
3. Run the standalone `jekyll` app:

    *Example: Running the OSX version*

    ```shell
    $ jekyll-3.2.0-osx.tgz/jekyll --version
    jekyll 3.2.0
    ```

    > NOTE: The above examples use the OSX version. For Linux versions everything is the same, but `{platform}` in all strings like `jekyll-3.2.0-{platform}` should be replaced with the appropriate platform; `linux-x86` or `linux-x86_64`
