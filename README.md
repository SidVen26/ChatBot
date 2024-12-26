# Movie/TvRecBot 

I used code related to the tutorial on [building a Python chatbot with ChatterBot](https://realpython.com/build-a-chatbot-python-chatterbot/), to begin building my chatBot and from there have built upon it to make a chat bot that recommends tv/movies to a user.

To use my chatBot:

Create and activate a [virtual environment](https://realpython.com/python-virtual-environments-a-primer/), then install the necessary dependencies:

```sh
$ python -m venv venv
$ source venv/bin/activate
(venv) $ python -m pip install -r requirements.txt
```

Then you can navigate into the folder `source_codel/` and train and start the interactive command-line interface chatbot by running `bot.py`:

```sh
(venv) $ cd source_code_final
(venv) $ python bot.py
`

The bot will learn from the replies you give and improve its accuracy. You can quit the interactive prompt by typing any of the `exit_conditions` defined in `bot.py`.



You'll find the code for each step of the tutorial in a separate folder. The folders also include a SQLite database that contains the different phases of training at each step. Because of this, you can inspect the project at different stages and notice how it evolves when you add more data and interactions.
<h3>Next steps </h3>
<p>I'm going to create a GUI for my chatbot, and continue to give it more prompts to train and build up its accuracy and make it more user friendly</p>
