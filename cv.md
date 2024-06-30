# Demchuk Tatiana
## Contact information:
* Phone: +79969329782
* Mail: tanya_demchuk_isvp@mail.ru
* Discord: hikabuchi
* GitHub: Hikabuchi
## Aabout me
I'm studying at college to become a web developer, and in this course I want to consolidate basic knowledge.
## Skills
* C#
* JavaScript
* Figma
* Git
* HTML5
* CSS3
* React
* PHP
## Code
Simple filter by category
```
const checkboxes = document.querySelectorAll('.category-filters input[type="checkbox"]');
const productCards = document.querySelectorAll('.product');

checkboxes.forEach((checkbox) => {
  checkbox.addEventListener('change', () => {
    const selectedCategories = [];
    let showAll = false;

    checkboxes.forEach((checkbox) => {
      if (checkbox.checked) {
        if (checkbox.value === 'all') {
          showAll = true;
        } else {
          selectedCategories.push(checkbox.value);
        }
      }
    });

    productCards.forEach((productCard) => {
      if (showAll) {
        productCard.style.display = 'block';
      } else if (selectedCategories.includes(productCard.dataset.category)) {
        productCard.style.display = 'block';
      } else {
        productCard.style.display = 'none';
      }
    });
  });
});
 ```
## Work experience
There is non-commercial development experience in the center for digital education "it-cube"
## Education
Khakass polytechnic college Specialty - "Information systems and programming" qualification web developer. 3nd year.


