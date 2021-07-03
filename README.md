# gramosint

* The Instagram OSINT Tool gets a range of information from an Instagram account that you normally wouldn't be able to get
from just looking at their profile

* The information includes:

* [ profile ] : user id, followers / following, number of uploads, profile img URL, business enum, external URL, joined Recently, etc

* [ tags & mentions ] : most used hashtags and mentioned accounts

* [ email ] : if any email is used any where it'll be displayed

* [ posts ] : accessability caption, location, timestamp, caption, picture url, etc
  * ( yet not working correctly with posts instagram marks as 'sensitive cotent' )  

---

## • How To Install

`$ pkg install -y git`

`$ git clone https://github.com/pedulimuapa/osintgram.git && cd osintgram`

`$ python3 -m pip install -r requirements.txt`

## • Usage

`$ python3 main.py -u username`

`$ python3 main.py -h`

`-p, --post images info highlight`


## • Update
 
`$ git pull`

