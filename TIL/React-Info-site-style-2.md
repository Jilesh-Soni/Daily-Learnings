## CSS
### ::marker
- styles the bullets !
.main--facts > li::marker {
    font-size: 1.4rem;
    
}
- font-size might misalign the text !


### background image instead of img html element !

main {
    padding: 57px 27px;
    color: white;
    background-image: url(./images/react-icon-large.png);
    background-repeat: no-repeat;
    background-position-x: right;
    background-position-y: 75%;
}
### project

flex: 0 0 auto;         /* ADD */
display: flex;          /* ADD */
flex-direction: column; /* ADD */

.card--title {
    overflow: hidden;
    text-overflow: ellipsis;
}
card to be reltive then a div that's absolute !

{...item} in props !

const [meme, setMeme] = React.useState({
        topText: "",
        bottomText: "",
        randomImage: "http://i.imgflip.com/1bij.jpg" 
    })
 

## JSX renders arrays !

const paragraphs = pokemon.map(mon => {
    return `<p>${mon}</p>`
})
