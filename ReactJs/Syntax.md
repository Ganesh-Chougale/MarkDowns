### inline css:  
```jsx
    <h1 style={{ color: 'orange', textAlign: 'center', fontSize: '40px' }}>Jai Shree Ram</h1>
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

