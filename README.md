# libft

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![42 Roma Luiss](https://img.shields.io/badge/42_Roma_Luiss-000000?style=flat-square&logo=42&logoColor=white)

My own C library, the first project at 42. It reimplements part of libc and adds helpers that I reused in all the later C projects.

- **libc**: `ft_strlen`, `ft_memcpy`, `ft_memmove`, `ft_strlcpy`, `ft_strlcat`, `ft_strnstr`, `ft_atoi`, `ft_calloc`, `ft_strdup` …
- **Extra**: `ft_substr`, `ft_split`, `ft_itoa`, `ft_strmapi`, `ft_striteri`, `ft_putnbr_fd` …

```bash
make        # produces libft.a
cc main.c -L. -lft
```

---

<sub>Part of my 42 Roma Luiss curriculum · [more projects](https://github.com/Fbiondo00) · MIT License</sub>
