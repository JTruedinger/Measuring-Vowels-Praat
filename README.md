# Readme
This script was created as part of a course that I taught at the University of Bayreuth and was supposed to serve as a introduction to scripting in Praat.
It runs well, but it's far from perfect. Feel free to use and change the script in any way you like. However, please cite
it (see below). I added a "change log" and a to-do list, but work on the script is currently paused.

# Use:
The script only measures formant values of certain specified sounds. There are some further tips in the script itself. All you soundfiles and textgrid files should
be in the same folder, and they should have the same name. Only the type (.wav/.mp3/.textgrid) should differ. The script supposes a 3-tier textgrid: phoneme, word, and text.
More shouldn't be an issue.

1. Run script
2. Specify file directory
3. Specify the name of the outputfile. The .csv suffix is mandatory. By default, the output is saved in the same path you put the script. If you want to save it somewhere else, see (step 8)
4. Specify the phoneme tier.
5. Specify the phoneme you want to measure.
6. Specify the word tier.
7. Specify the gender of the speaker. The script only differentiates between male/female. This is needed for the formant settings.
8. Change output file path if needed.
9. Click okay and you're good to go.

The script measure the formants at the midpoint by default. You can just change that. A few different timepoints are already supplied.

# How to cite:
Trüdinger, Johanens (2024). Measuring Vowels_Script. https://github.com/JTruedinger.
