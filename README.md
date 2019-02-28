# Responsive Design Using The Mobile First Approach

## The Goal
The goal is to practice building a one page website that adapts to the size of the browser window changing due to the site being viewed on different devices

## Sample code

### html

`<section class="section">
            <div class="vcenter">
                <article class="article column column-60">
                    <p class="section-paragraph">
                    Lorem ipsum dolor sit amet, consectetur adi
                    </p>
                </article>
                <aside class="aside column column-40">
                    <p class="section-paragraph">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Esse numquam neque possimus, pariatur. Recusandae, obcaecati! Aspernatur quaerat et reiciendis aperiam dolor, incidunt quas expedita nostrum nobis maiores accusamus sint non aliquid porro aut cumque perferendis fugiat unde ullam amet eaque? Quidem ipsum accusamus, quisquam quaerat tempore, hic adipisci vel cum!
                    </p>
                </aside>
            </div>`

### css

` .vcenter{
    position: relative;
    top: 50%;
    transform: translateY(-50%);
}`

`@media (min-width: 768px) {
    .column {
    float: left;
    }
    .column-60 {
        width: 60%;
}`
    
`   .column-40 {
        width: 40%;
    }
}` 