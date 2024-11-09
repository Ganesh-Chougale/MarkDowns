### inline css:  
```jsx
    <h1 style={{
  color: 'orange',
  textAlign: 'center',
  fontSize: '40px',
  fontFamily: 'Arial, sans-serif',
  fontWeight: 'bold',
  fontStyle: 'italic',
  letterSpacing: '2px',
  lineHeight: '1.5',
  textTransform: 'uppercase',
  textDecoration: 'underline',
  textShadow: '2px 2px 5px rgba(0,0,0,0.5)',
  backgroundColor: 'yellow',
  padding: '10px 20px',
  margin: '20px',
  border: '2px solid black',
  borderRadius: '10px',
  boxShadow: '0px 4px 6px rgba(0, 0, 0, 0.1)',
  width: 'auto',
  height: 'auto',
  display: 'inline-block',
  cursor: 'pointer',
  opacity: 1, // or any value between 0 and 1 for transparency
  zIndex: 10,
  transform: 'scale(1.1)',
  transition: 'all 0.3s ease-in-out',
  visibility: 'visible',
  position: 'relative', // or 'absolute', 'fixed'
  top: '10px',
  left: '20px',
  right: '30px',
  bottom: '40px',
  overflow: 'hidden',
  whiteSpace: 'nowrap',
  transformOrigin: 'center',
  animation: 'spin 2s linear infinite', // you can create your own animation
  objectFit: 'contain', // for images or videos
  objectPosition: 'center center', // for controlling positioning of images or videos
  clipPath: 'circle(50%)', // for clipping shapes
  backdropFilter: 'blur(5px)', // applies a blur effect on the background
  boxSizing: 'border-box', // helps with padding and borders
  alignItems: 'center', // flexbox alignment
  justifyContent: 'center', // flexbox alignment
  flexDirection: 'column', // flexbox direction
  flexWrap: 'wrap', // flexbox wrap
  alignSelf: 'center', // flexbox alignment for a specific item
  overflowX: 'hidden', // controls horizontal overflow
  overflowY: 'auto', // controls vertical overflow
  maxWidth: '100%',
  minWidth: '100px',
  maxHeight: '200px',
  minHeight: '50px',
  opacity: 1, // or any value between 0 and 1 for transparency
  filter: 'grayscale(50%)', // filter effect, like grayscale, sepia, etc.
  transform: 'rotate(15deg)' // rotate the element
}}>
  Jai Shree Ram
</h1>

```  
### moduler css:  
```jsx
# JSx
import style from './ExpenseTracker.module.css'

function ExpenseTracker() {
  return (
    <div className={style.ExpenseTracker}>
      <h1>This is an header</h1>
    </div>
  )
}

export default ExpenseTracker

```  
```css
# module.css
.ExpenseTracker{
    background-color: #fff;
}
```  

