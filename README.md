import pyshorteners
url=input("https://www.meesho.com/?srsltid=AfmBOorMu6fHNpIQq5Y3V-CbghDa-FPu2B1Zn_1FzXcm7pH7iXvWH2hl")
def shortenurl(url):
    s=pyshorteners.Shortener()
    print(s.tinyurl.short(url))
    shortenurl(url)
    v
