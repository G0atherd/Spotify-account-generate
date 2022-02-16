
# Description
this is a new application for creating accounts to see how the application itself works: this is a python3 script uses a module to send fake http / s requests also uses iOS-user agnet which contributes to the speed of the script.
The script works with the new spotify API, the script will work until they change the spotify API.
By using any of the files available in this repository, you understand that you are agreeing to use at your own risk. All files available here are for education and / or research only.

# Requirements
requests module: pip install requests

# Usage
Simply run it without arguments to generate one account and print its credentials to the console:
python spotify_generator.py

You can also specify the amount of accounts to generate and a file where their credentials will be saved:
python spotify_generator.py -n AMOUNT -o OUTPUT_FILE

The creadentials will be printed/saved in the following format:
NICKNAME:USERNAME:EMAIL:PASSWORD

# credit
https://github.com/davide-acanfora/spotify-account-generator
What is the difference between my script and his mine is with the new API his with the old one, he uses android user-agent I use iOS user-agent I also added proxy-server.

# Discord!
https://discord.gg/aKtZ2Qbjds

# Update
Expect more script updates soon...
