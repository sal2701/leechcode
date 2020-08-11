# leechcode
Python script to fetch details about leetcode questions useful for planning interview preparation.

I have created a Google Sheet using this data, this might be useful for last moment preparation as well as revision. Hope you find it useful.

[:link: The Google Sheet](https://docs.google.com/spreadsheets/d/1KfZq_onP06UDqizkLOjraOfw2qIODDqMyd-3knUu3hA/edit?usp=sharing)


### How to use the script?
We basically need to send requests to the server as an authenticated user so we have to find those details.

- Login to leetcode and go to any problem.
- Open the Network panel ( Ctrl + Shift + E ) and reload.
- Search for a ```graphql``` request in the big list, a small window will open to the right.
- Click the ```Headers``` and scroll to find the ```Request Headers```.
- Copy below 2 values from here and paste them in the code
  - ```Cookie```
  - ```x-csrftoken```
- Run the code ```python3 leech.py```.



### How to edit the data?
Use the Pandas library to modify the data as it is very convenient.
