from env import get_db_url
import pandas as pd


url = get_db_url("employees")
sql = """
SELECT * FROM employees LIMIT 20
"""

df = pd.read_sql(sql, url)
df.head()