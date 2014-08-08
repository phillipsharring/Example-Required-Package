# Example-Package

An example package for use with the Satis Server talk.

## Installation

### Git

```bash
$ git clone git@github.com:philsown/Example-Package.git Example-Package
$ cd Example-Package
$ php composer.phar install -o
```

### Composer

Add something like this to your `composer.json` file.

```json
{
    "repositories": [
        {
            "url": "https://github.com/philsown/Example-Package.git",
            "type": "git"
        }
    ],
    "require": {
        "philsown/Example-Package": "dev-master"
    }
}
```	

## I Made This

Author:  [Phillip Harrington](http://www.phillipharrington.com/).
