# MINIGREP and how to use it

## how to set up project :file_folder:

```
1) download this repo
```

## how to use :question:

### poem.txt
```
Tunga steg, tystnad 
Ledsna noter och symfonier
Lätta steg, lystnad
Glada rytmer och melodier

Kollar ned, blundar
Bara mörker, kom fantasier
Kollar upp, lundar
Friska skogar, harmonier
```

Get lines containing keyword by writing:
> **$ cargo run _keyword_ _filename.txt_**

Example, getting lines containing **_er_**:
> **$ cargo run er poem.txt**

### output
```
Ledsna noter och symfonier
Glada rytmer och melodier
Bara mörker, kom fantasier
Friska skogar, harmonier
```

Notice that the program is CASE SENSITIVE:
> **$ cargo run L poem.txt**

### output
```
Ledsna noter och symfonier
Lätta steg, lystnad
```

Do following to make the program CASE INSENSITIVE:
> **$ CASE_INSENSITIVE=1 cargo run L poem.txt**

### output
```
Ledsna noter och symfonier
Lätta steg, lystnad
Glada rytmer och melodier
Kollar ned, blundar
Kollar upp, lundar
```

To save the output into a new file simply write:
> **$ cargo run L poem.txt > _filename.txt_**

### _filename.txt_
```
Ledsna noter och symfonier
Lätta steg, lystnad
```

### bugs & cons :warning:
* unknown at this point

### contributions :trophy:
* you could be on this list

### communication :speech_balloon:
:email: if you have any questions feel free to mail me at isakhorvath@gmail.com

:beers: know how to improve the code? feel free to send a pull request! open for collaboration

:headphones: wanna hang out, talk about programming or work on a project? add me on discord: tavro#9198

:coffee: feeling generous? buy me a coffe https://www.buymeacoffee.com/CvaPyAznK

:star: if you found this useful or interesting I would appreciate a star 
