# Prasad Golla Durga
## Section: 01

<br>

* [Input file](https://github.com/GD-Prasad/gd-wrangle/blob/main/data.txt)

<br>

* [Output File 1](https://github.com/GD-Prasad/gd-wrangle/blob/main/resultSpeaker_1.txt)
* [Output File 2](https://github.com/GD-Prasad/gd-wrangle/blob/main/resultSpeaker_2.txt)

<br>

## Submission:

* Name of the Play Assigned: SCENE I. Britain. The garden of Cymbeline's palace.
* Speaker 1: QUEEN
* Speaker 2: CYMBELINE
* Question: We had to find which speaker spoke the most is the play.
#### [Commands used:](https://github.com/GD-Prasad/gd-wrangle/blob/main/commands.txt)
* To copy/ download the File:``` powershell curl "http://shakespeare.mit.edu/cymbeline/full.html" -O "data.txt" ```
* To count the number of times speaker spoke and put it to a file ``` bash grep -c "Queen" data.txt > resultSpeaker_1.txt ```
* To count the number of times speaker 1 spoke and put it to a file: ``` bash grep -c "CYMBELINE" data.txt > resultSpeaker_2.txt ```
* Speaker 2 ( CYMBELINE) won the Contest.
