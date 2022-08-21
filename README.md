# g_o_t_quotes.py
Web-API for [gameofthronesquotes.xyz](https://gameofthronesquotes.xyz) website to retrieve some quotes of Game of Thrones

## Example
```python
import g_o_t_quotes.py
g_o_t_quotes = g_o_t_quotes.GameOfThronesQuotes()
random_quote = g_o_t_quotes.get_random_quote()
print(random_quote)
```
