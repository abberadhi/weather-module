This is a precompiled ShellCheck binary.
      https://www.shellcheck.net/

ShellCheck is a static analysis tool for shell scripts.
It's licensed under the GNU General Public License v3.0.
Information and source code is available on the website.

This binary was compiled on Mon Apr 26 18:24:45 UTC 2021.



      ====== Latest commits ======

commit 331e89be990547b6e21ad1b6e56065bcda1ba053
Author: Vidar Holen <spam@vidarholen.net>
Date:   Mon Apr 26 10:33:36 2021 -0700

    Fix bad warning for ${#arr[*]}. Fixes #2218.
