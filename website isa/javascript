let cart = [];

document.querySelectorAll('.add-to-cart').forEach(button => {
    button.addEventListener('click', () => {
        const shoeName = button.previousElementSibling.textContent; // Extrahiert den Schuhnamen
        cart.push(shoeName);
        alert(shoeName + " wurde in den Warenkorb gelegt.");
    });
});