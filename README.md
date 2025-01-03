# Movie/TvRecBot 

I used code related to the tutorial on [building a Python chatbot with ChatterBot](https://realpython.com/build-a-chatbot-python-chatterbot/), to begin building my chatBot and from there have built upon it to make a chat bot that recommends tv/movies to a user.

<h3>Next steps:</h3>
<p>I'm going to create a GUI for my chatbot and continue to give it more prompts to train and build up its accuracy and make it more user friendly</p>


<h3>To use my chatbot:</h3>

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
