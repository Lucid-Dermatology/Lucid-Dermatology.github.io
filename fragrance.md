### Fragrance Mix

The purpose of this document is to demonstrate how Lucid Dermatology App performs product recommendation if user selected **Fragrance Mix** allergen.
 
When a user selects **Fragrance Mix**, our algorithm recognizes products as **UNSAFE** if the product has at least one of the following ingredients or at least one synonym of the following chemicals. (You can see list of synonyms for each chemical by clicking on it name)

* Fragrance
* [a-Amylcinnamaldehyde](https://luciddermatology.com/synonyms/Amylcinnamaldehyde)
* [Cinnamaldehyde](https://luciddermatology.com/synonyms/Cinnamaldehyde)
* [Cinnamyl alcohol](https://luciddermatology.com/synonyms/Cinnamyl-alcohol)
* [Eugenol](https://luciddermatology.com/synonyms/Eugenol)
* [Geraniol](https://luciddermatology.com/synonyms/Geraniol)
* [Hydroxycitronellal](https://luciddermatology.com/synonyms/Hydroxycitronellal)
* [Isoeugenol](https://luciddermatology.com/synonyms/Isoeugenol)

So, our algorithm check 65 chemical names when user selected **Fragrance Mix**, and mark product as "unsafe" in case of any of chemicals were found.

