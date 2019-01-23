# -*- coding: utf-8 -*-

from selenium import webdriver
import urllib
from bs4 import BeautifulSoup

from urllib import parse

path = "C:/Users/Q/Downloads/chromedriver_win32/chromedriver.exe"

driver = webdriver.Chrome(path)

words = "내일 날씨 어때"

test = ""

num =0

check1 = "알려"

check2 = "검색"

check3 = "찾아"

check4 = "뭐야"

check5 = "어때"

if check1 in words:
    print("검색 할게요")
    num = words.find(check1)
    test = words[:num-1]
    test = test.split(' ')
    print(test)
elif check2 in words:
    print("검색 할게요2")
    num = words.find(check2)
    test = words[:num-1]
    test = test.split(' ')
    print(test)
elif check3 in words:
    print("검색 할게요3")
    num = words.find(check3)
    test = words[:num - 1]
    test = test.split(' ')
    print(test)
elif check4 in words:
    print("검색 할게요4")
    num = words.find(check4)
    test = words[:num - 1]
    test = test.split(' ')
    print(test)
elif check5 in words:
    print("검색 할게요5")
    num = words.find(check5)
    test = words[:num - 1]
    test = test.split(' ')
    print(test)
else:
    print("없음")

search = test

query = {"q" : " ".join(search)}



driver.get('https://www.google.com/search?'+urllib.parse.urlencode(query))


driver.implicitly_wait(5)


