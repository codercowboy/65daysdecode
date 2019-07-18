# 65daysdecode

An attempt to decode cryptic the band [65daysofstatic's instagram](https://www.instagram.com/65daysofstatic/?hl=en) posts from the summer of 2019.

The latest version of this is probably here: https://github.com/codercowboy/65daysdecode

Originally authored in July of 2019 by [Jason Baker](mailto:jason@onejasonforsale.com). 

# running the code

To run the code, open the 65daysdecode.html file in the chrome browser. Simply loading the file will run the embedded javascript inside the file and log output to the developer console.

# contributing

If someone wants to clean up or contribute to the code. Send me PRs or [email me](mailto:jason@onejasonforsale.com) your changed file. I'll give you credit in this readme.

# current results

Current results show the messages aren't necessarily ciphered in a one to one manner, and there's already one example of a ciphered character being used twice, which also suggests the message ciphering may just be random noise :(

```
Now updating alphabet with known code from '6▜d▋▍▟o▞▝▐a▝░' to '65daysofstati'.
Mapping character #0: 6 (54) -> 6 (54)
Mapping character #1: ▜ (9628) -> 5 (53)
Mapping character #2: d (100) -> d (100)
Mapping character #3: ▋ (9611) -> a (97)
Mapping character #4: ▍ (9613) -> y (121)
Mapping character #5: ▟ (9631) -> s (115)
Mapping character #6: o (111) -> o (111)
Mapping character #7: ▞ (9630) -> f (102)
Mapping character #8: ▝ (9629) -> s (115)
Mapping character #9: ▐ (9616) -> t (116)
Mapping character #10: a (97) -> a (97)
Mapping character #11: ▝ (9629) -> t (116)
Error Pre-existing mapped char '▝ (9629)' -> s (115)' exists, overriding it with 't (116)'.
Mapping character #12: ░ (9617) -> i (105)
Finished updating alphabet with known code from '6▜d▋▍▟o▞▝▐a▝░' to '65daysofstati'.

decoded posts:
6▜d▋▍▟o▞▝▐a▝░ -> 65daysofttati
▂e▄l▀c▖░▟▍▎▏▛ -> ▂e▄l▀c▖isy▎▏▛
r▌p▒▊▋▗▐▂▐▟ -> r▌p▒▊a▗t▂ts
{▙e▉_▆r▐▜l▁█r} -> {▙e▉_▆rt5l▁█r}
r▐▜l▁cr▍▎▏▛ -> rt5l▁cry▎▏▛
▊▔r▐▓▄▊▛▞▎▍▖▎▟ -> ▊▔rt▓▄▊▛f▎y▖▎s
▉▐▄▅▎▋▁▐▋65▄ep▋ -> ▉t▄▅▎a▁ta65▄epa
r▅p▖▊c▙//▖/2019 -> r▅p▖▊c▙//▖/2019
▜▜▞▏▚▕▋▒▂▝░▋░ -> 55f▏▚▕a▒▂tiai
▍▂█▜▂▇▉▀▓▒ -> y▂█5▂▇▉▀▓▒
||▂|▒▅▊▒▂▟ -> ||▂|▒▅▊▒▂s
▆▟▉▗▘020▚0▔|| -> ▆s▉▗▘020▚0▔||
▓▂r▒▒rr▓▍rr▅ -> ▓▂r▒▒rr▓yrr▅
█r▇▟▖r▃▟▛▖▗r -> █r▇s▖r▃s▛▖▗r
l▋▅▐▟▛pl▛▚r -> la▅ts▛pl▛▚r
▞>▞▂▚▕▋▎▗;░e -> f>f▂▚▕a▎▗;ie
▜▇▒▅▇▔▀▃▛▘ -> 5▇▒▅▇▔▀▃▛▘
r▓▂r▒▒rr▓▍rr▅ -> r▓▂r▒▒rr▓yrr▅
█r▇▟▖r▃▟▛▖▗ -> █r▇s▖r▃s▛▖▗
r▖▞l▁▗▆,▄▎▉▌ -> r▖fl▁▗▆,▄▎▉▌
▀█▜▎▊▙▛▋▒▗▔▌r -> ▀█5▎▊▙▛a▒▗▔▌r
▁▇▃l▟▖█▁▓█▌▃ -> ▁▇▃ls▖█▁▓█▌▃
▌▖▜░▏▍▎▏▛ -> ▌▖5i▏y▎▏▛
▋▒▊▃▚ -> a▒▊▃▚

alphabet debug:
, (44) -> null
/ (47) -> null
6 (54) -> 6 (54)
a (97) -> a (97)
d (100) -> d (100)
o (111) -> o (111)
{ (123) -> null
| (124) -> null
} (125) -> null
▀ (9600) -> null
▁ (9601) -> null
▂ (9602) -> null
▃ (9603) -> null
▄ (9604) -> null
▅ (9605) -> null
▆ (9606) -> null
▇ (9607) -> null
█ (9608) -> null
▉ (9609) -> null
▊ (9610) -> null
▋ (9611) -> a (97)
▌ (9612) -> null
▍ (9613) -> y (121)
▎ (9614) -> null
▏ (9615) -> null
▐ (9616) -> t (116)
░ (9617) -> i (105)
▒ (9618) -> null
▓ (9619) -> null
▔ (9620) -> null
▕ (9621) -> null
▖ (9622) -> null
▗ (9623) -> null
▘ (9624) -> null
▙ (9625) -> null
▚ (9626) -> null
▛ (9627) -> null
▜ (9628) -> 5 (53)
▝ (9629) -> t (116)
▞ (9630) -> f (102)
▟ (9631) -> s (115)
```


# License

All content (documentation, source code) is licensed with the [Apache license](http://en.wikipedia.org/wiki/Apache_license), which is a great license because it:

* a) covers liability - my code should work, but I'm not liable if you do something stupid with it
* b) allows you to copy, fork, and use the code, even commercially
* c) is [non-viral](http://en.wikipedia.org/wiki/Viral_license), that is, your derivative code doesn't *have to be* open source to use it

Other great licensing options for your own code: [BSD License](https://en.wikipedia.org/wiki/BSD_licenses), [MIT License](https://en.wikipedia.org/wiki/MIT_License), or [Creative Commons](https://en.wikipedia.org/wiki/Creative_Commons_license).

Here's the license:

Copyright (c) 2018, Coder Cowboy, LLC. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* 1. Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.

* 2. Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.
  
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
[INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
[INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
  
The views and conclusions contained in the software and documentation are those
of the authors and should not be interpreted as representing official policies,
either expressed or implied.


