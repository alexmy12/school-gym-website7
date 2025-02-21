document.addEventListener("DOMContentLoaded", function() {
    let services = document.querySelectorAll(".services div");

    services.forEach((service, index) => {
        service.style.opacity = "0";
        service.style.transform = "translateY(50px)";
        setTimeout(() => {
            service.style.transition = "opacity 1s ease-in-out, transform 1s ease-in-out";
            service.style.opacity = "1";
            service.style.transform = "translateY(0)";
        }, index * 300);
    });
});
