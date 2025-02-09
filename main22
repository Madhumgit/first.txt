function openTab(event, sectionId) {
    
    let tabContents = document.getElementsByClassName("tabcontent");
    for (let i = 0; i < tabContents.length; i++) {
        tabContents[i].style.display = "none";
    }

  
    let activeSection = document.getElementById(sectionId);
    activeSection.style.display = "block";
    activeSection.scrollIntoView({
        behavior: "smooth",
        block: "start"
    });


    let tabButtons = document.getElementsByClassName("tablinks");
    for (let i = 0; i < tabButtons.length; i++) {
        tabButtons[i].classList.remove("active");
    }

    event.currentTarget.classList.add("active");
}
function changeImage() {
    let img = document.getElementById("dynamicImage");
    if (img.src.includes("image1.png")) {
        img.src = "image2.png"; 
    } else {
        img.src = "image1.png"; 
    }
}



