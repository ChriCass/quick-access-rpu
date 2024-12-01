<style scoped>
.img-fluid {
  max-width: 80%;
  height: auto;
  object-fit: cover;
}

.card-horizontal {
    display: flex;
    margin: 1rem 0;
    max-width: 500px;
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease; /* Animación para el crecimiento y el cambio de color */
}

.card-img {
    width: 150px;
    height: 150px;
    object-fit: cover;
}

.card-content {
    padding: 15px;
    flex: 1;
}

.card-title {
    font-size: 1.25rem;
    font-weight: bold;
    margin-bottom: 10px;
    color: black; /* Color por defecto */
}

.card-text {
    font-size: 1rem;
    margin-bottom: 15px;
    color: #555; /* Color por defecto */
}

.card-link {
    color: #007bff;
    text-decoration: none;
    font-size: 1rem;
}

.card-link:hover {
    text-decoration: underline;
}

a{
    text-decoration: none;
}

/* Estilo para el hover */
.card-horizontal:hover {
    background-color: #68b7b2;
    cursor: pointer;
    transform: scale(1.05); /* Hace que la card crezca */
}

 /* Cambiar color del SVG a blanco en hover */
.card-horizontal:hover svg {
    fill: white !important; /* Cambia el color del SVG */
}
.card-horizontal:hover .card-title,
.card-horizontal:hover .card-text,
.card-horizontal:hover .card-link {
    color: white; /* Cambia el color del texto a blanco en hover */
}
</style>
<template>
  <div class="container my-5 py-5">
   
    <div class="row justify-content-center">
      <div class="col-12 col-lg-5">
        <a href="">
        <div class="card-horizontal">
            <div class="d-flex align-items-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="card-img"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              style="fill: rgba(0, 0, 0, 1); transform:; msfilter:"
            >
              <path
                d="M6 22h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2zm3-3H7v-2h2v2zm0-4H7v-2h2v2zm0-4H7V9h2v2zm4 8h-2v-2h2v2zm0-4h-2v-2h2v2zm0-4h-2V9h2v2zm4 8h-2v-6h2v6zm0-8h-2V9h2v2zM6 4h12v3H6V4z"
              ></path>
            </svg>
          </div>

          <div class="card-content">
            <h5 class="card-title">Metamsur - sistema de Cajas</h5>
            <p class="card-text">
              Sistema en version estable, manejo de ingresos, egresos, CXP, CXC con generación de
              reportes en tiempo real
            </p>
           
          </div>
        </div>
    </a>
    <a href="">
        <div class="card-horizontal">
          <div class="d-flex align-items-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="card-img"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              style="fill: rgba(0, 0, 0, 1); transform:; msfilter:"
            >
              <path
                d="M6 22h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2zm3-3H7v-2h2v2zm0-4H7v-2h2v2zm0-4H7V9h2v2zm4 8h-2v-2h2v2zm0-4h-2v-2h2v2zm0-4h-2V9h2v2zm4 8h-2v-6h2v6zm0-8h-2V9h2v2zM6 4h12v3H6V4z"
              ></path>
            </svg>
          </div>

          <div class="card-content">
            <h5 class="card-title">Lat S.A.C. - sistema de Cajas</h5>
            <p class="card-text">
              Sistema en version estable, manejo de ingresos, egresos, CXP, CXC con generación de
              reportes en tiempo real
            </p>
           
          </div>
        </div>
    </a>
      </div>
      
      <div class="col-12 col-lg-2 d-flex flex-column align-items-center justify-content-center">
        <div class="d-flex justify-content-center">
          <img src="../assets/single-logo.png" class="img-fluid" alt="" />
        </div>
      </div>
      <div class="col-12 col-lg-5">
        <a href="">
        <div class="card-horizontal">
          <img src="https://via.placeholder.com/150" class="card-img" alt="Imagen de ejemplo" />
          <div class="card-content">
            <h5 class="card-title">Título de la Card</h5>
            <p class="card-text">
              Este es un texto de ejemplo para la card. Aquí puedes describir el contenido o
              cualquier otra información relevante.
            </p>
            
          </div>
        </div>
    </a>
    <a href="">
        <div class="card-horizontal">
          <img src="https://via.placeholder.com/150" class="card-img" alt="Imagen de ejemplo" />
          <div class="card-content">
            <h5 class="card-title">Título de la Card</h5>
            <p class="card-text">
              Este es un texto de ejemplo para la card. Aquí puedes describir el contenido o
              cualquier otra información relevante.
            </p>
 
          </div>
        </div>
    </a>
      </div>
    </div>
  </div>
</template>
