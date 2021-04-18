# Track-location-using-phonenumber
import phonenumbers
# if you want to change phone number then simple change value of number variable
number="+91 6376496690"
from phonenumbers import geocoder
print(number)
ch_number=phonenumbers.parse(number,"CH")
print(ch_number)
print(geocoder.description_for_number(ch_number,"en"))

from phonenumbers import carrier
serive=phonenumbers.parse(number,"RO")
print(carrier.name_for_number(serive,"en"))
