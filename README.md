<h1 align="center">
  <a href="https://www.npmjs.com/package/instavim"><img src="http://rishigiri.com/github/instavim.png" alt="Instavim" width="400"></a>
  <br>
</h1>

> A small tool to download profile pictures, public images and videos available on instagram directly from command line.

## Install

```
$ npm install --global instavim
```

## Usage

```
    Usage : cli.js <command> [info] <option> [info]           

    Commands:

          u   ❱  instagram username ➨➤ High Resolution
          m   ❱  insatgram username ➨➤ Medium Resolution
          w   ❱  insatgram username ➨➤ Low Resolution
          l   ❱  full link to download image
          v   ❱  full link to download video

    Options:

          -n  ❱  save image or video as                    [required]

    Examples:

         instavim -u [user-name] -n [image-name]
         instavim -l [imageLink] -n [image-name]
         instavim -v [videoLink] -n [video-name]

    Missing required argument: n

```
## Examples
```
Copy and paste the following command to check it's functionality.
```

### Profile picture of a user in full resolution

__PUBLIC ACCOUNT__

```
instavim -u iam_rishig -n rishi
```
__PRIVATAE ACCOUNT__

```
instavim -u isma_shahid -n instaUser
```
### Pofile picture of a user in medium resolution
```
isntavim -m iam_rishig -n rishiMed
```

### Profile picture of a user in low resolution
```
instavim -w iam_rishig -n rishiSM
```

### Public Image uploaded by an instagram user
```
instavim -l https://www.instagram.com/p/BC2pgFRoUO4/ -n sindresorhus
```

### Public Video uploaded by an instagram user
```
instavim -v https://www.instagram.com/p/BD661xeA_V1/ -n buttshit
```

## Screenshot


## Related

Image-of    [ CLI TOOL ](https://github.com/CodeDotJS/image-of)

Gravatar-of [ CLI TOOL ](https://github.com/CodeDotJS/gravatar-of)

## License

MIT | Copyright &copy; [Rishi Giri](http://rishigiri.com)
