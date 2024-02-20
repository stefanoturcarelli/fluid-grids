# Fluid Grids

![image](https://github.com/stefanoturcarelli/fluid-grids/assets/67341828/f481a2dc-986f-46db-ac77-591d0485eea7)

`target / context = result`

200px -> target

960px -> context

200 / 960 = 0.2083 * 100 = 20.83% -> result

aprox. 20% of its parent (context)

```css
html,
body {
  margin: 0;
  padding: 0;
}

.wrap {
  max-width: 1400px;
  margin: 0 auto; 
}

.header {
  width: 100%;
  height: 130px;
  background-color:  #038c5a;
}

.left {
  height: 625px;
  width: 20.83%;
  background-color: #000;
  display: inline-block;
}
```

# References

- [Fluid Grids by Ethan Marcotte - March 03, 2009](https://alistapart.com/article/fluidgrids/)
