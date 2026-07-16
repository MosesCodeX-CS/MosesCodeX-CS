```
● moses.service - Software Engineer, Systems & Security
     Loaded: loaded (/kenya/nairobi-ish; enabled)
     Active: active (running) since ~forever ago
       Docs: github.com/MosesCodeX-CS
    Process: fixes-what-breaks.sh --priority=urgent
   Main PID: 1 (never dies, only restarts)
      Tasks: too many, see `systemctl list-projects`
     Uptime: 420 days without a reboot (bragging rights, not a typo)
```

<div align="center">
<img src="https://komarev.com/ghpvc/?username=MosesCodeX-CS&label=connections+received&color=00E5FF&style=flat-square"/>
<img src="https://img.shields.io/github/followers/MosesCodeX-CS?style=flat-square&label=watching"/>
<img src="https://img.shields.io/github/stars/MosesCodeX-CS?style=flat-square&label=starred+by+humans"/>
</div>

---

### `$ journalctl -u moses.service --since "always"`

```
[BOOT]     Kenya. Networking cables. A very patient Cisco instructor.
[INFO]     Started fixing routers before fixing code felt natural.
[INFO]     Discovered PHP. Was told it's dead. Ignored the memo.
[WARN]     Attempted chess.com rating climb. Queen sacrificed unintentionally.
[INFO]     Installed Parrot OS. Removed the mouse from the equation.
[INFO]     Compiled Neovim config. Has not left it since.
[CRIT]     Told a hospital "yes, I can monitor your oxygen plant."
[INFO]     It worked. Nobody panicked. 10/10 outcome.
[ONGOING]  Still building things that are not allowed to fail quietly.
```

---

### `$ ps aux --sort=-priority | grep moses`

```
USER   PID   PROJECT       STAT   %FOCUS  COMMAND
moses  0001  OPMAS-001     R      92%     laravel + pymodbus --mode=read-only
moses  0002  NyumbaFind    R      85%     laravel + postgres --with=mpesa,otp
moses  0003  Bingwa        S      60%     flutter kotlin --survive=doze-mode
moses  0004  sleep         Z      04%     (defunct, rarely called)
```

**`OPMAS-001`** — Hospital oxygen plant monitor. Polls Modbus TCP, watches the gauges so a human doesn't have to walk there at 2am. Deliberately **read-only** — the one process on this list not allowed to touch anything.

**`NyumbaFind`** — Kenya rental marketplace. Real OTP auth, real M-Pesa STK Push, real design system. Built so house-hunting stops depending on a guy named "Agent Dennis" and his one blurry photo.

**`Bingwa`** — Android app that automates bundle purchases over USSD. Survived a full war against Android's Doze mode, wakelock races, and a bug where the app mistook the time `05:38` for a menu option. It's still running. So is the app.

---

### `$ apt list --installed | grep moses-stack`

```
laravel/framework .......... backend, opinionated, unbothered
php ......................... still cool, no debate accepted
python3-pymodbus ............ hardware whisperer
flutter & kotlin ............ mobile, fighting the OS for survival
postgresql / mysql .......... where the truth lives
parrot-os .................... daily driver, zero regrets
neovim + lua ................. home
bspwm / i3wm / kitty / rofi .. terminal aesthetics, taken seriously
nginx / supervisor ........... keeps things alive after I log off
docker ....................... [pending] — ask again next quarter
```

---

### `$ traceroute moses --skills networking`

```
 1  cisco-fundamentals.local     0.3ms   verified, not vibes-based
 2  subnetting.gateway           1.1ms   can still do it on paper
 3  it-support.legacy            2.4ms   the "have you tried restarting it" era
 4  cybersecurity.upstream       4.7ms   currently building this hop
 5  ***                          ***     request timed out (still learning)
```

---

### `$ cat /var/log/dev-humor.log`

```
[Chess.com]  flagged another blunder.
[Chess.com]  has never once flagged a race condition. Missed opportunity.

[Debug session]  4 hours spent on a lockscreen crash.
[Root cause]     a regex matched "05:38" as a USSD menu item.
[Lesson learned] clocks and menus should never share a parser.

[Commit message]  "read-only, I promise" — every OPMAS-001 commit,
                   just in case future-me gets ambitious.

[Uptime claim]  420 days without a crash.
[Reality]        or nobody's checked the logs in 420 days. Unclear.
```

---

### `$ github-stats --user MosesCodeX-CS`

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=MosesCodeX-CS&show_icons=true&theme=tokyonight&hide_border=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MosesCodeX-CS&layout=compact&theme=tokyonight&hide_border=true"/>
</div>

<!-- If the streak badge below is asleep (Heroku free-tier does that), swap the src for:
     https://streak-stats.demolab.com/?user=MosesCodeX-CS&theme=tokyonight&hide_border=true -->
<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=MosesCodeX-CS&theme=tokyonight&hide_border=true"/>
</div>

---

### `$ man moses`

```
NAME
       moses — fixes networks, ships systems, occasionally sleeps

SYNOPSIS
       moses [--collaborate] [--report-bug] [--just-say-hi]

DESCRIPTION
       Builds software for people who cannot afford it to break:
       hospitals, tenants, agents, telco resellers. Does not build
       software to impress a portfolio. Occasionally builds software
       to win an argument about PHP.

SEE ALSO
       github.com/MosesCodeX-CS — the process list is public.

EXIT STATUS
       Has not exited yet. See --uptime above.
```

<div align="center">

*"First solve the problem, then write the code."*
*— some wise person, probably mid-`:wq`*

</div>
