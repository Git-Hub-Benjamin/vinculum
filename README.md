# Vinculum - My Personal Linktree

A nice looking and expandable static site to showcase all my important links. Vinculum means "bond," "tie," "chain," or "fetter" in latin

## HAdding more links

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