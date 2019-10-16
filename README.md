# 42_test
Used for testing during peer-to-peer evaluations.

# Norm
`python <(curl -s https://raw.githubusercontent.com/mmbatha/test/mmbatha-patch-1/pynorm.py)`, a variant of `https://github.com/richard-dp/pynorm`

# Libftest
`git clone https://github.com/jtoty/Libftest`

# LibC Functions #1
`bash grademe.sh ft_strlen ft_isalpha ft_isdigit ft_isalnum ft_isascii ft_isprint`

# LibC Functions #2
`bash grademe.sh ft_toupper ft_tolower ft_memchr ft_strchr ft_strrchr ft_bzero`

# LibC Functions #3
`bash grademe.sh ft_memcpy ft_strcpy ft_strcat ft_strcmp ft_strstr ft_memmove ft_memcmp`

# LibC Functions #4
`bash grademe.sh ft_strlcat ft_strdup ft_atoi ft_memccpy ft_strnstr ft_strncmp ft_strncpy ft_strncat`

# Additional Functions #1
`bash grademe.sh ft_memalloc ft_putchar ft_putstr ft_putendl ft_putnbr ft_strnew ft_strdel ft_strclr ft_strequ ft_strnequ ft_strsub ft_strjoin ft_putchar_fd ft_putstr_fd ft_putendl_fd ft_putnbr_fd`

# Additional Functions #2
`bash grademe.sh ft_memdel ft_striter ft_striteri ft_strmap ft_strmapi ft_strtrim ft_strsplit ft_itoa`

# Bonus part (if it exists)
`bash grademe.sh ft_lstnew ft_lstadd ft_lstdelone ft_lstdel ft_lstiter ft_lstmap`

# 42FileChecker
`git clone https://github.com/jgigault/42FileChecker`

# get_next_line
`git clone https://github.com/mmbatha/GNL-1.git`
## -- Files to copy
`cp GNL-1/bible.txt corr/`
`cp GNL-1/gnl* corr/`
`cp GNL-1/test_* corr/`
`cd corr/`
## -- Shells to run
`sh gnl_intra_test.sh`
`sh gnl.sh`
## -- Actual tests
`./test_gnl bible.txt`
`./test_gnl test_m38.txt`
`./test_gnl test_huge.txt`
`./test_gnl test_lines.txt`
`./test_gnl test_lines2.txt`
`./test_gnl test_eminem.txt`
`./test_gnl test_lorem_5para.txt`
`./test_gnl test_one_big_fat_line.txt`
(c) 2019 Courtesy of Damothepirate

# memory leaks
`leaks [process ID or name] >> leaks.txt`

# detect leaks
[Leak Detector](leak_detector_c)

# Swingy
`mvn --version`
## -- Files to check 
`pom.xml`
`swingy.iml`
## -- Compile
`mvn clean package`

# Peer Video
https://youtu.be/B2ThaazAhEA

# PHP Bootcamp
## Day 03
## Clone
`git clone [] ~/Desktop/MAMP/apache2/htdocs/mmcorr`
## ex00
`sh ~/Desktop/MAMP/ctlscript.sh start`
## ex01
`curl 'http://localhost:8080/mmcorr/ex01/phpinfo.php'`
## ex02
`curl 'http://localhost:8080/mmcorr/ex02/print_get.php?login=mmbatha&evaluator=Monde'`

`curl 'http://localhost:8080/mmcorr/ex02/print_get.php?&=&login=mmbatha&&evaluator=Monde'`
## ex03
`curl -c cook.txt 'http://localhost:8080/mmcorr/ex03/cookie_crisp.php?action=set&name=plat&value=choucroute'`

`curl -b cook.txt 'http://localhost:8080/mmcorr/ex03/cookie_crisp.php?action=get&name=plat'`

`curl -c cook.txt 'http://localhost:8080/mmcorr/ex03/cookie_crisp.php?action=del&name=plat'`

`curl -b cook.txt 'http://localhost:8080/mmcorr/ex03/cookie_crisp.php?action=get&name=plat'`
## ex04
`curl 'http://localhost:8080/mmcorr/ex04/raw_text.php'`
## ex05
`curl --head 'http://localhost:8080/mmcorr/ex05/read_img.php'`
## ex06
`curl --user root:root 'http://localhost:8080/mmcorr/ex06/members_only.php'`

`curl --user zaz:root 'http://localhost:8080/mmcorr/ex06/members_only.php'`

`curl --user zaz:ilovemylittlepony 'http://localhost:8080/mmcorr/ex06/members_only.php'`

## Day 04
## ex00
`curl -vc cook.txt 'http://localhost:8080/mmcorr/ex00/index.php'`

`curl -vb cook.txt 'http://localhost:8080/mmcorr/ex00/index.php?login=sb&passwd=beeone&submit=OK'`

`curl -vb cook.txt 'http://localhost:8080/mmcorr/ex00/index.php'`

`curl -v 'http://localhost:8080/mmcorr/ex00/index.php'`

## ex01
'rm htdoc/private/passwd`

`curl -d login=toto1 - passwd=titi1 -d submit=OK 'http://localhost:8080/mmcorr/ex01/create.php'`
