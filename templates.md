Templates can be specified in 3 ways, this is in the components metadata.

### Inline Template

```
template: '<h1>{{pageTitle}}</h1>'
```

### Inline Template Over Lines

This uses ES 2015 backticks `

```
template: `
<div>
<h1>{{pageTitle}}</h1>
<div>
	Component Text
</div>
</div>
`
```

### Linked Template

Template URL for longer templates, this will then offer design time syntax checking in your Editor.

```
templateUrl: './product-list.component.html'
```

