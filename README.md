# NHS.UK experimental patterns

**This is not a pattern library.**


This a growing collection of patterns emerging from NHS.UK beta prototypes. They will continue to be iterated on. They are in no way finished or finalised.

- [Base](#base)
- [Callout](#callout)
- [Panel](#panel)


## Base

- Font TBC
- Body copy 20px
- Baseline grid 4px
- All margins, padding and line heights should be multiples of 4
- Headings in sentence case

### Headings

![Headings](base/headings.png)

### Body copy

![Headings](base/paragraph.png)

### Bullet list

![Headings](base/list/bullets.png)

### Numbered list

![Headings](base/list/numbered.png)

### Chevron list list

![Headings](base/list/chevron.png)

```
list--chevron
```


## Callout

Callouts are used to draw attention to a particular piece of content and/or prompt people to take action.  

#### Notes

- Six variants which roughly correspond with the urgency of the action to be taken
- Different border styles are used to differentiate other than by colour

### Muted

![Muted callout](callout/muted.png)

```
callout callout--muted
```

### Info

![Info callout](callout/info.png)

```
callout callout--info
```

### Attention

![Attention callout](callout/attention.png)

```
callout callout--attention
```

### Warning

![Warning callout](callout/warning.png)

```
callout callout--warning
```

### Alert

![Alert callout](callout/alert.png)

```
callout callout--alert
```

### Severe

![Alert callout](callout/severe.png)

```
callout callout--severe
```

### Compact

- Tighter padding
- Makes callout flow to width of content
- Can be applied to any callout

![Info callout](callout/info-compact.png)

```
callout callout--compact
```

## Panel

- Mini content assembly
- Orientation/understanding/action

### Panel with header

![Alert callout](panel/header.png)

```
panel 
panel__header
panel__content
```

### Panel with footer

![Alert callout](panel/footer.png)

```
panel 
panel__content
panel__footer
```
