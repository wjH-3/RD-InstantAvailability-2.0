# RD-InstantAvailability-2.0

Simple Python script to check if a torrent is **Instantly Available** (cached) in Real-Debrid. A substitute for the `/instantAvailability` Real-Debrid API endpoint since its removal. Enter your RD API token and the Magnet Link that you wish to check and it will output the result, i.e if the torrent is instantly available or not.

Also used in [Mediarr](https://github.com/wjH-3/Mediarr), another personal project for Real-Debrid much larger in scale.

## Prerequisites
1. [Python](https://www.python.org/downloads/)
2. `requests` Python module (installation: `pip install requests`)
3. [Real-Debrid](https://real-debrid.com/premium) Premium account

## Usage
1. Downlaod `instant.py` into your system
2. In a Terminal, 
```
python instant.py
```
3. Enter your Real-Debrid API token, which can be found [here](https://real-debrid.com/apitoken).
4. Enter/paste in your Magnet Link to check for `Instant Availability`

*Note:* You can also hard-code your APi token into the script itself so that you don't have to enter it each time when running the script. To do so, in `main()`, change `api_token` into: 
```
api_token = "YOUR_API_TOKEN_HERE"
```