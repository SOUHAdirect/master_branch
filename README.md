# master_branch
QA_project

from datetime import *
import pytz
import time
date_now=datetime.now()
print('Time now',date_now)
timestamp_linux=datetime.timestamp(date_now)
print(timestamp_linux)

d=pytz.timezone("utc")
f=datetime.now(d)

d=pytz.timezone("Europe/Paris")
dU=pytz.timezone("UTC")
f=datetime.now(d)
FO=datetime.now(dU)
print(f)
print(FO)


# converte fromtimpstamp to datetiem
ts = 1617295943.17321
# convert to datetime
dt = datetime.fromtimestamp(ts)
print(dt)
# transfromer une date de string en date
srting='2023-04-19 16:59:58'

ddd=datetime.strftime(srting,'%d-%m-%Y, %H:%M:%S')



# timstp=1681836100000
