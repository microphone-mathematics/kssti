# kxss
[1.1]: http://i.imgur.com/tXSoThF.png
[1]: https://twitter.com/TobiunddasMoe
This a adaption of Emoe's adaptation of tomnomnom's kxss tool to test for SSTI.

All Credit for this Code goes to [Tomnomnom](https://github.com/tomnomnom/) and [Emoe](https://github.com/Emoe/)

## Changes to original kxss
I changed the output format of kxss to make it better grepable for my recon script. My new Output Looks like this:
```
URL: https://www.**********.***/event_register.php?event=177 Param: event Unfiltered: [" ' < >]
```

## Installation
To install this Tool please use the following Command:
```
go get github.com/microphone-mathematics/kssti
```

## Usage
To run this script use the following command:
```
echo "https://www.**********.***/event_register.php?event=177" | kssti
```

## Question
If you have an question you can create an Issue or ping me on [![alt text][1.1]][1]
