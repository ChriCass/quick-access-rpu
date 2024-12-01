<style scoped>
.hero-section {
  background-image: url('../assets/hero_image.jpeg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  min-height: 100vh;
  position: relative;
  display: flex;
  color: white;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.hero-section::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(#489aca, #29636cf3, #68b7b2bd);
}

.container {
  position: relative;
  z-index: 1;
}

.c-heading {
  font-size: clamp(32px, 5vw, 56px);
}
.img-fluid {
  max-width: 20%;
  height: auto;
  object-fit: cover;
}

.custom-button {
  border: none;
  outline: none;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  transition: all ease-in-out 200ms; /* Equivalente a transition-all ease-in-out duration-200 */
  border-radius: 0.375rem; /* Equivalente a rounded-md */
  gap: 0.5rem; /* Equivalente a gap-x-2 */
  font-size: 0.875rem; /* Equivalente a text-sm */
  padding: 0.5rem 1rem; /* Equivalente a px-4 py-2 */
  color: white;
  background-color: #008080; /* Equivalente a bg-emerald-500 */
}

.custom-button:hover {
  color: white;
  background-color: #059669; /* Equivalente a hover:bg-emerald-600 */
}

.custom-button:focus {
  color: white;
  background-color: #059669; /* Equivalente a focus:bg-emerald-600 */
  box-shadow: 0 0 0 2px #10b981; /* Equivalente a focus:ring-emerald-600 */
}

.custom-button:disabled {
  opacity: 0.8; /* Equivalente a disabled:opacity-80 */
  cursor: not-allowed;
}

.dark .custom-button {
  background-color: #064e3b; /* Equivalente a dark:bg-emerald-700 */
}

.dark .custom-button:hover {
  background-color: #059669; /* Equivalente a dark:hover:bg-emerald-600 */
}

.dark .custom-button:focus {
  background-color: #059669; /* Equivalente a dark:focus:bg-emerald-600 */
  box-shadow: 0 0 0 2px #10b981; /* Equivalente a dark:focus:ring-emerald-600 */
}

.down-arrow {
  display: inline-block;
  font-size: 3rem;

  text-decoration: none;
  animation: bounce 1s infinite;
  cursor: pointer;
  transition: transform 0.3s ease;
}

.down-arrow:hover {
  transform: scale(1.1);
}

.arrow {
  display: block;
  animation: bounce 1s infinite;
}

@keyframes bounce {
  0% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(10px);
  }
  100% {
    transform: translateY(0);
  }
}

 
</style>

<template>
  <main class="hero-section">
  
    <div class="container">
      <div class="flex justify-content-center flex-column align-items-center text-center">
        <h1 class="c-heading mb-4">Encuentra el sistema que deseas</h1>
        <p class="lead">
          Accede de manera rápida y sencilla a todos los sistemas que tenemos disponibles.
        </p>
        <div class="d-flex flex-column justify-content-center">
          <div class="mx-3"><button class="custom-button">ir a las opciones</button></div>
          <a href="#section" class="down-arrow">
            <span class="arrow">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="80"
                height="80"
                viewBox="0 0 24 24"
                style="fill: #489aca"
              >
                <path
                  d="m12 15.586-4.293-4.293-1.414 1.414L12 18.414l5.707-5.707-1.414-1.414z"
                ></path>
                <path
                  d="m17.707 7.707-1.414-1.414L12 10.586 7.707 6.293 6.293 7.707 12 13.414z"
                ></path></svg
            ></span>
          </a>
        </div>
      </div>
    </div>
  </main>
</template>

 


