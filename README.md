#Libft

This is our first '42 school' project.
It's goal is for us to understand how libaries work and to create our own libary. 
For a lot of the upcoming C projects we are not allowed to use any libary functions other than self written functions.

## Libft functions

### Single character functions

- `int  ft_isalpha(int c)`-  is c part of the alphabet?
- `int  ft_isdigit(int c)`-  is c a digit?
- `int  ft_isalnum(int c)`-  is c part of the alphabet or digit?
- `int  ft_isascii(int c)`-  is c part of the ASCII chart?
- `int  ft_isprint(int c)`-  is c a printable character?
- `int  ft_toupper(int c)`-  c to uppercase.
- `int  ft_tolower(int c)`-  c to lowercase.

### String functions

- `int  ft_atoi(const char *nptr)`-  string to int.
- `char*    ft_itoa(int n)`-  int to allocated string.
- `char*    ft_strchr(const char *s, int c)`-  point to first occurrence of c in s.
- `char*    ft_strrchr(const char *s, int c)`-  pointer to last occurrence of c in s.
- `int  ft_strncmp(const char *s1, const char *s2, size_t n)`-  compare n charackters of s1 and s2.
- `size_t   ft_strlen(const char *s)` : length of string.
- `size_t   ft_strlcpy(char *dst, const char *src, size_t size)` : copy size chars of src to dst
- `size_t   ft_strlcat(char *dst, const char *src, size_t size)` : concatenate src to dst.
- `char*    ft_strdup(const char *s)` : duplicate string.
- `char*    ft_substr(char const *s, unsigned int start, size_t len)` : copy and return the substring of s that begins at start and ends at start + len.
- `char*    ft_strjoin(char const *s1, char const *s2)` : join s1 to s2.
- `char*    ft_strtrim(char const *s1, char const *set)` : trim the chars in set from s1.
- `char**   ft_split(char const *s, char c)` : split string s in as many words as are separated by c.
- `char*    ft_strmapi(char const *s, char (*f)(unsigned int, char))` : map f onto s.
- `void ft_striteri(char *s, void (*f)(unsigned int, char*))` : apply f to every char in s.
