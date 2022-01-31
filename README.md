# command-line-world
A quick reference for doing day-to-day things in command line



## Brightness

Run `brightnessctl --help` for more details
```sh
brightnessctl s 40%
```

## Changing Volume of Sound cards
`amixer scontrol` to see all the controls

```sh
alsamixer
# or
# amixer set <control-name> <volume>
amixer set Master 40%
```


## Headphones
`pacmd list-cards` command shows the all the available sound cards      

In each index, under profiles section, available profiles will be there, to set any profile 
```sh
# pacmd set-card-profile <index> <profile-name>
pacmd set-card-profile 1 handsfree_head_unit
```

