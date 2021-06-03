# SVG создание спрайта

 [ Генератор спрайтов SVG](https://cldup.com/https://svgsprit.es/)

## Snippet vscode
```
{
	"SVG-спрайты": {
		"prefix": "_svg",
		"body": [
			"<svg class=\"$2\">",
			"  <use xlink:href=\"./img/svg/sprite.svg#$1\"></use>",
			"</svg>"
		],
		"description": "SVG-спрайты"
	}
}

```