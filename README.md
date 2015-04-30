# goodhost

Simple host file management in Go.

<img src="http://www.hangthebankers.com/wp-content/uploads/2013/09/Masks-Rothschild-party1.jpg" width=400><br>
[A Surrealist Parisian Dinner Party chez Madame Rothschild, 1972](http://www.messynessychic.com/2013/08/27/a-surrealist-parisian-dinner-party-chez-madame-rothschild-1972/)

## command-line usage

### list all lines

```
$ goodhost list
```

### check for ip/host pair

```
$ goodhost check 127.0.0.1 google.com 
```

### add an ip/host

```
$ goodhost add 127.0.0.1 google.com
```

### remove a line 

```
$ goodhost remove 127.0.0.1 google.com
```
