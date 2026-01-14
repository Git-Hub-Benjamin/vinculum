# Vinculum - My Personal Linktree

A nice looking and expandable static site to showcase all my important links

## How to Add More Links

Edit `config.js` and add a new object to the `links` array:

```javascript
{
    id: "unique-id",
    title: "Link Title",
    description: "Brief description",
    url: "https://example.com",
    icon: "emoji-icon",
    color: "#hexcolor"
}
```

## Customization

- **Profile Name**: Edit `config.js` → Set the name in the HTML
- **Background**: Modify the gradient in `styles.css` → `body` selector
- **Colors**: Update link colors in the `config.js` color properties
