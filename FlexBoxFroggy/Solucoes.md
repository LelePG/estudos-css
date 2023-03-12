## Nível 1
```css
#pond {
	display: flex;
	justify-content: flex-end;
}
```

## Nível 2
```css
#pond {
	display: flex;
	justify-content: center;
}
```

## Nível 3
```css
#pond {
	display: flex;
	justify-content: space-around;
}
```

## Nível 4
```css
#pond {
	display: flex;
	justify-content: space-between;
}
```

## Nível 5
```css
#pond {
	display: flex;
	align-items:flex-end;
}
```

## Nível 6
```css
#pond {
	display: flex;
	justify-content: center;
	align-items:center;
}
```

## Nível 7
```css
#pond {
	display: flex;
	justify-content: space-around;
	align-items: flex-end;
}
```

## Nível 8
```css
#pond {
	display: flex;
	flex-direction: row-reverse;
}
```

## Nível 9
```css
#pond {
	display: flex;
	flex-direction: column;
}
```

## Nível 10
```css
#pond {
	display: flex;
	flex-direction: row-reverse;
	justify-content: flex-end;
}
```

## Nível 11
```css
#pond {
	display: flex;
	flex-direction:column;
	justify-content:flex-end;
}
```

## Nível 12
```css
#pond {
	display: flex;
	flex-direction: column-reverse;
	justify-content: space-between;
}
```

## Nível 13
```css
#pond {
	display: flex;
	flex-direction: row-reverse;
	justify-content:center;
	align-items: flex-end;
}
```

## Nível 14
```css
#pond {
	display: flex;
}

.yellow {
	order:3;
}
```
- A propriedade `order` serve para organizar os itens em grupos de ordem, ou *ordinal groups*. 
- O valor da propriedade order é o número que representa o grupo
- Os itens são colocados na ordem dos grupos,  ou seja, o grupo 1 aparece antes do grupo 2, que aparece depois do grupo 3, etc. 
- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Ordering_Flex_Items#the_order_property)

## Nível 15
```css
#pond {
	display: flex;
}

.red {
	order:-3;
}
```

## Nível 16
```css
#pond {
	display: flex;
}

.yellow {
	align-self:flex-end;
}
```

## Nível 17
```css
#pond {
	display: flex;
}

.yellow {
	align-self: flex-end;
	order:1;
}
```

## Nível 18
```css
#pond {
	display: flex;
	flex-wrap: wrap;
}
```

## Nível 19
```css
#pond {
	display: flex;
	flex-direction: column;
	flex-wrap: wrap;
}
```

## Nível 20
```css
#pond {
	display: flex;
	flex-flow: column wrap;
}
```

## Nível 21
```css
#pond {
	display: flex;
	flex-wrap:wrap;
	align-content:flex-start;
}
```

## Nível 22
```css
#pond {
	display: flex;
	flex-wrap:wrap;
	align-content:flex-end;
}
```

## Nível 23
```css
#pond {
	display: flex;
	flex-wrap:wrap;
	flex-direction:column-reverse;
	align-content: center;
}
```

## Nível 24
```css
#pond {
	display: flex;
	flex-flow: column-reverse wrap-reverse;
	justify-content: center;
	align-content: space-between;
}
```

