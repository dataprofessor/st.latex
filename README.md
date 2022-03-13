# st-latex

`st.latex` display mathematical expressions formatted as LaTeX.

## Demo app
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/st-latex/)

## Code
Contents of the `streamlit_app.py` file:
```python
import streamlit as st

st.header('st.latex')

st.latex(r'''
     a + ar + a r^2 + a r^3 + \cdots + a r^{n-1} =
     \sum_{k=0}^{n-1} ar^k =
     a \left(\frac{1-r^{n}}{1-r}\right)
     ''')
```

## References
Read about [`st.latex`](https://docs.streamlit.io/library/api-reference/text/st.latex) in the Streamlit API Documentation.
