jQuery-calculator
=================

jQuery calculator plugin that does exactly what it says :)


Usage
-----


### The HTML

```html

<div class="calculator">

	<table class="calc-table">

		<tr class="calc-row">
			<td colspan="4">
				<input type="text" class="screen" id="screen" placeholder="0" disabled/>
			</td>
		</tr>
		<tr class="calc-row">
			<td class="calc-btn operator">(</td>
			<td class="calc-btn operator">)</td>
			<td class="calc-btn operator percentage">%</td>
			<td class="calc-btn operator del special">AC</td>
		</tr>
		<tr class="calc-row">
			<td class="calc-btn">7</td>
			<td class="calc-btn">8</td>
			<td class="calc-btn">9</td>
			<td class="calc-btn operator" data-key="/">&divide;</td>
		</tr>
		<tr class="calc-row">
			<td class="calc-btn">4</td>
			<td class="calc-btn">5</td>
			<td class="calc-btn">6</td>
			<td class="calc-btn operator">-</td>
		</tr>
		<tr class="calc-row">
			<td class="calc-btn">1</td>
			<td class="calc-btn">2</td>
			<td class="calc-btn">3</td>
			<td class="calc-btn operator" data-key="*">x</td>
		</tr>
		<tr class="calc-row">
			<td class="calc-btn">0</td>
			<td class="calc-btn">.</td>
			<td class="calc-btn equals special">=</td>
			<td class="calc-btn operator">+</td>
		</tr>

	</table>

</div>

```


### The JS

```javascript
$('.calculator').calc({
	'theme' : 'dark'
});

```

#### Dependencies

jQuery 1.8+