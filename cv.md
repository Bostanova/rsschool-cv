## Zukhra Bostanova

## Contacts
* Address: Moscow, Russia
* Email: bostanzuhra@gmail.com
* Github: [Bostanova](https://github.com/Bostanova)

# About me
All users only see the web interface. So I want to know how websites are created and how they work.

# Skills
* HTML/CSS (basics)
* C (basics)
* git 
* Editors: VSCode

# Code example
```
#include "libft.h"

char *ft_strstr(const char *haystack, const char *needle){
	char	*s1;
	char	*s2;
	char	*res;
	int		cmp;

	s1 = (char *)haystack;
	s2 = (char *)needle;
	if (s2[0] == '\0')
		return (s1);
	res = ft_strchr(s1, s2[0]);
	if (res){
		cmp = ft_strncmp(res, s2, (ft_strlen(s2)));
		if (cmp == 0)
			return (res);
	}
	return (NULL);
}
```

# Work experience
You can see my projects on my [github](https://github.com/Bostanova)

# Courses
* School21 (School of Programming)

# Language
English - A2