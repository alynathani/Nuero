<template>
    <div class="container">
        <img src="./icons/network.svg">
        <h1>
            Neuro.
        </h1>
        <p>
            Find a professional to give <strong>science + research</strong> oriented advice, for self-advancement.
        </p>
        <div class="optionsContainer">
            <button class="SignUpButton">Sign Up</button>
            <button class="LogInButton">Log In</button>
        </div>
    </div>
    
</template>

<style>


.container{
    margin: auto;
    text-align: center;
    width: 60%;
    padding: 5% 0;
    font-family: 'Merriweather', serif;
}

.container h1{
    font-size: 7rem;
}

.container p{
    font-size: 2.5rem;
}

img {
    height: 7rem;
}

.optionsContainer{
    margin-top: 2rem;
    margin-right: auto;
    margin-left: auto;
    display: flex;
    justify-content: space-evenly;
    width: 40%;
}

.LogInButton {
    font-size: 1.5rem;
    padding: 0.7rem;
    background-color: rgb(68, 172, 68);
    color: white;
    border-radius: 0.5rem;
    border: none;
}

.SignUpButton {
    font-size: 1.5rem;
    padding: 0.7rem;
    background-color: blue;
    color: white;
    border-radius: 0.5rem;
    border: none;
}

</style>