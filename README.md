# Libft

This is our first project at '42 School.'  
The goal is to help us understand how libraries work and to create our own library.  
For many of the upcoming C projects, we are not allowed to use any library functions except for those we write ourselves.

## Libft functions

## Single Character Functions

- `int ft_isalpha(int c)` – checks if `c` is a letter.
- `int ft_isdigit(int c)` – checks if `c` is a digit.
- `int ft_isalnum(int c)` – checks if `c` is a letter or digit.
- `int ft_isascii(int c)` – checks if `c` is an ASCII character.
- `int ft_isprint(int c)` – checks if `c` is a printable character.
- `int ft_toupper(int c)` – converts `c` to uppercase.
- `int ft_tolower(int c)` – converts `c` to lowercase.

## String Functions

- `int ft_atoi(const char *nptr)` – converts a string to an int.
- `char* ft_itoa(int n)` – converts an int to a string.
- `char* ft_strchr(const char *s, int c)` – returns a pointer to the first occurrence of `c` in `s`.
- `char* ft_strrchr(const char *s, int c)` – returns a pointer to the last occurrence of `c` in `s`.
- `int ft_strncmp(const char *s1, const char *s2, size_t n)` – compares up to `n` characters of `s1` and `s2`.
- `size_t ft_strlen(const char *s)` – returns the length of `s`.
- `size_t ft_strlcpy(char *dst, const char *src, size_t size)` – copies up to `size` characters from `src` to `dst`.
- `size_t ft_strlcat(char *dst, const char *src, size_t size)` – appends `src` to `dst` up to `size`.
- `char* ft_strdup(const char *s)` – duplicates the string `s`.
- `char* ft_substr(char const *s, unsigned int start, size_t len)` – returns a substring from `s` starting at `start` with length `len`.
- `char* ft_strjoin(char const *s1, char const *s2)` – concatenates `s1` and `s2`.
- `char* ft_strtrim(char const *s1, char const *set)` – trims characters in `set` from `s1`.
- `char** ft_split(char const *s, char c)` – splits `s` into words separated by `c`.
- `char* ft_strmapi(char const *s, char (*f)(unsigned int, char))` – applies `f` to each character of `s`.
- `void ft_striteri(char *s, void (*f)(unsigned int, char*))` – applies `f` to each character of `s` with its index.

## String Finding Functions

- `int ft_match(const char *big, const char *little, size_t len)` – checks if `little` is found in `big` within `len` characters.
- `char* ft_strnstr(const char *big, const char *little, size_t len)` – finds the first occurrence of `little` in `big`, searching up to `len` characters.
- `char* ft_grep(char **tab, char *word)` – searches for `word` in the `tab` array, similar to the shell command `grep`.

## File Descriptor (fd) Functions

- `void ft_putchar_fd(char c, int fd)` – writes the character `c` to the file descriptor `fd`.
- `void ft_putstr_fd(char *s, int fd)` – writes the string `s` to the file descriptor `fd`.
- `void ft_putendl_fd(char *s, int fd)` – writes the string `s` followed by a newline to the file descriptor `fd`.
- `void ft_putnbr_fd(int n, int fd)` – writes the integer `n` as a decimal to the file descriptor `fd`.

## List Functions (Bonus)

- `t_list* ft_lstnew(void *content)` – creates a new list node with `content`.
- `void ft_lstadd_front(t_list **lst, t_list *new)` – adds the node `new` to the front of the list `lst`.
- `int ft_lstsize(t_list *lst)` – returns the number of nodes in the list `lst`.
- `t_list* ft_lstlast(t_list *lst)` – returns the last node of the list `lst`.
- `void ft_lstadd_back(t_list **lst, t_list *new)` – adds the node `new` to the end of the list `lst`.
- `void ft_lstdelone(t_list *lst, void (*del)(void *))` – deletes one node from the list using the `del` function to free the content.
- `void ft_lstclear(t_list **lst, void (*del)(void *))` – clears the entire list, freeing all nodes and using the `del` function to free their content.
- `void ft_lstiter(t_list *lst, void (*f)(void *))` – applies the function `f` to each node in the list `lst`.
- `t_list* ft_lstmap(t_list *lst, void *(*f)(void *), void (*del)(void *))` – creates a new list by applying the function `f` to each node in `lst`, using `del` to free content if needed.

