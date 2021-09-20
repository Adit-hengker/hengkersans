# hengkersans
import requests,bs4,sys,os,subprocess,getpass,hashlib
import random,time,re,json
import emailerendem,calendar,nande,orbxd
from datetime import datetime
from datetime import date 
from concurrent.futures import ThreadPoolExecutor
from mechanize import Browser
from multiprocessing.pool import ThreadPool
from bs4 import BeautifulSoup as parser
from requests.exceptions import ConnectionError
from mechanize import Browser
if 'linux' in sys.platform.lower():
    N = '\x1b[1;94m'
    G = '\x1b[1;92m'
    O = '\x1b[1;97m'
    R = '\x1b[1;91m'
try:
    import requests
except ImportError:
    os.system('pip2 install requests')
else:
    try:
        import mechanize
    except ImportError:
        os.system('pip2 install mechanize')
    else:
        try:
            import bs4
        except ImportError:
            os.system('pip2 install bs4')
