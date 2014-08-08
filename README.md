# Example-Required-Package

An example required package for use with the Satis Server talk.

## Installation

### Git

```bash
$ git clone git@github.com:philsown/Example-Required-Package.git Example-Required-Package
$ cd Example-Required-Package
$ php composer.phar install -o
```

### Composer

Add something like this to your `composer.json` file.

```json
{
    "repositories": [
        {
            "url": "https://github.com/philsown/Example-Required-Package.git",
            "type": "git"
        }
    ],
    "require": {
        "philsown/Example-Required-Package": "dev-master"
    }
}
```	

## I Made This

Author:  [Phillip Harrington](http://www.phillipharrington.com/).