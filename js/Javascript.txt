document.addEventListener("DOMContentLoaded", function() {

const form = document.getElementById("contactForm");

if(form){
form.addEventListener("submit", function(e){
e.preventDefault();

document.getElementById("successMessage").textContent =
"Merci ! Votre message a été envoyé avec succès.";

form.reset();
});
}

});
