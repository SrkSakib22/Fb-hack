# Fb-hackdef keluar():
	print "\033[1;96m[!] \x1b[1;91mExit"
	os.sys.exit()


def acak(b):
    w = 'ahtdzjc'
    d = ''
    for i in x:
        d += '!'+w[random.randint(0,len(w)-1)]+i
    return cetak(d)


def cetak(b):
    w = 'ahtdzjc'
    for i in w:
        j = w.index(i)
        x= x.replace('!%s'%i,'\033[%s;1m'%str(31+j))
    x += '\033[0m'
    x = x.replace('!0','\033[0m')
    sys.stdout.write(x+'\n')


def jalan(z):
	for e in z + '\n':
		sys.stdout.write(e)
		sys.stdout.flush()
		time.sleep(00000.1)


##### LOGO #####
logo = """
\033[1;91m       🚫🚫🚫———————————————————————————————🚫🚫🚫
\033[1;96m        
\033[1;96m█████████████████████\033[1;96m███
\033[1;96m█▄─▄▄─█▄─▄▄▀█─▄▄─█▄─▄\033[1;96m▄▀█
\033[1;96m██─▄█▀██─▄─▄─██─██─▄\033[1;96m─▄█
\033[1;96m▀▄▄▀▄▄▀\033[1;96m▄▄▀
\033[1;96m█████████████████████\033[1;96m███████
\033[1;96m█─▄─▄█─▄▄─█▄─▀─▄█▄─▄\033[1;96m█─▄▄▄─█
\033[1;96m██████─██▀██─█\033[1;96m█─███▀█
\033[1;96m▀▀▄▄▄▀▀▄▄▄▄▀▄▄█▄▄▀▄▄▄\033[1;96m▀▄▄▄▄▀           ;91m       🚫🚫🚫———————————————KING————————————————🚫🚫🚫
"""
def tik():
	titik = ['.   ','..  ','... ']
	for o in titik:
		print("\r\x1b[1;93mPlease Wait \x1b[1;93m"+o),;sys.stdout.flush();time.sleep(1)


back = 0
berhasil = []
cekpoint = []
oks = []
id = []
listgrup = []
vulnot = "\033[31mNot Vuln"
vuln = "\033[32mVuln"

os.system("clear")
print  """

\033[1;97m     ️   
\033[1;97m┏━━━┓╋╋╋╋╋╋╋┏━━━━┓
\033[1;97m┃┏┛╋╋╋╋╋╋╋┃┏┓┏┓┃
\033[1;97m┃━┳━━┳━┓┗┛┃┣┻━┳┓\033[1;97m┏┳┳━━┓
\033[1;97m┃┏━┫┏┫┏┓┃┏┛╋╋┃┏┓┣╋\033[1;97m╋╋┫┏━┛
\033[1;97m┃┗┛┃┃╋╋╋┃┃┃┗┛┣╋\033[1;97m╋┫┃┗━┓
\033[1;97m┗━┻┛┗━━┻┛╋╋╋┗┛┗━━┻┛\033[1;97m┗┻┻━━┛
\033[1;92m     
\033[1;97m     
\033[1;92m     
\033[1;97m     
\033[1;97m    
                                                               

"""

jalan("\033[1;97m•◈•───────•◈ We Are Bangladesh Black Hat Hackers •◈•───────•◈•")  
