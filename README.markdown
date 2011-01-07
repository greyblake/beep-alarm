# Beep Alarm
by Sergey Potapov (aka Blake)

## Intro 

By some reason I have no audio centre at the moment and my mobile can not make me awake.
So I decided to create this simple tool to wake me up. It is an alarm which uses a speaker to play music.

## Requirements

The alarm uses `beep` tool(make sure you have installed it) and bash interpreter.


## Usage

`beep_alarm [TIME] [OPTION VALUE]`

Options:

* `-r` - repeat times, if '-1' - play ifinity, defaut is 10
* `-f` - file with tune in Nokia format
* `-t` - tempo, default is 120
* `-m` - number of tune(melody)

Tunes:

* 0 - Kanlinka(russian song)
* 1 - Kino - Pachka Sigaret 
* 2 - Kino - Blood Type
* 3 - Metallica - Unforgiven
* 4 - Led Zeppelin - Stairway To Heaven
* 5 - Papa Roach - Last Resort
* 6 - Helloween - Power


## Examples

Play at 8 a.m. 20 times

    beep-alarm 08:00 -r 20

Play at 8 a.m. music from file

    beep-alarm 08:00 -f $HOME/nokia_music/kalinka.txt

Play right now with tempo=150 "Kino - Pachka Sigaret"

    beep-alarm -t 150 -m 1


## License

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License as
published by the Free Software Foundation; either version 2 of
the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place, Suite 330, Boston,
MA 02111-1307 USA
