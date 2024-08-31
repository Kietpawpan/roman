# roman.js
A JavaScript library for romanization of Thai names.

1. Load the roman library.
```
<script src="https://kietpawpan.github.io/roman/js/roman.js"></script>
```

2. Create an index file with the input box (id="thaiName").
```
<input  
  type="text" 
  id="thaiName" 
  value="" 
  placeholder="แม่-น้ำ เจ้า-พระ-ยา">
</input>
```

3. In the same index file, create the output textarea (id="romanize").
```
<textarea 
  id="romanize" 
  row="1" 
  cols="2" 
  style="height: 80px">
</textarea>
```

4. Also, create the Romanize botton, for running the romanization function, romanize().
```
<button 
   class="btn" 
   onclick="romanize()">
			<i 
		 	 class="fa fa-pencil">
			</i> 
   Romanize*
</button>
```

5. Then, create the Copy and the Clear buttons.
```
<button 
  class="btn" 
  onclick="copy()">
  Copy
</button>

<button 
  class="btn" 
  onclick="clearText()">
  Clear
</button>
```
## Example
[https://kietpawpan.github.io/roman/](https://kietpawpan.github.io/roman/)

## Version History

### 2.1 | Sep. 1, 2024
- New output format: Capitalized first letter of each word. 

### 2.0 | Sep. 1, 2024
- New UX, using w3.css.

### 1.0 | Sep 23, 2023
- Prototype  
