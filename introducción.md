<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>Descripción del paradigma orientado a objetos:</h1>
    </header>
    <main>
        <section>
            <p>
                La programación orientada a objetos es un paradigma de programación que organiza el código en torno a "objetos" en lugar de funciones o procedimientos aislados. Estos objetos son instancias de "clases", que actúan como plantillas o moldes que definen las propiedades y comportamientos que los objetos pueden tener.
                La programación orientada a objetos es importante porque organiza el código en objetos que reflejan el mundo real, facilitando su comprensión, mantenimiento y escalabilidad. Permite reutilizar código, simplifica problemas complejos y crea software robusto y adaptable, siendo esencial en lenguajes modernos como Java o Python. 
            </p>
        </section>
        <section>
            <h1>Los cuatro fundamentos de POO:</h1>
            <p>
             Los 4 fundamentos de la POO son: encapsulamiento, herencia, polimorfismo y abstracción.
             Encapsulamiento: Permite ocultar los detalles internos de un objeto y exponer solo lo necesario, protegiendo los datos y facilitando su manejo.
             Herencia: Permite que una clase derive de otra, reutilizando código y estableciendo relaciones jerárquicas.
             Polimorfismo: Permite que diferentes clases implementen un mismo método de manera distinta, adaptándose al contexto.
             Abstracción: Simplifica sistemas complejos al modelarlos mediante conceptos más generales y manejables.
            </p>
            <h1>Requisitos iniciales del sistema:</h1>
            <ol>
                <li><strong>Gestión de usuarios:</strong> El sistema debe permitir a los usuarios registrarse, iniciar sesión y cerrar sesión mediante credenciales seguras.</li>
                <li><strong>Procesamiento de datos:</strong> El sistema debe ser capaz de recibir, validar y procesar datos ingresados por el usuario según reglas predefinidas.</li>
                <li><strong>Almacenamiento de información:</strong> El sistema debe guardar los datos generados en una base de datos para su posterior consulta o modificación.</li>
                <li><strong>Generación de reportes:</strong> El sistema debe producir reportes o resúmenes basados en los datos almacenados, presentándolos en un formato legible.</li>
                <li><strong>Interacción entre objetos:</strong> El sistema debe permitir que diferentes objetos (como usuarios, productos o transacciones) interactúen entre sí según las reglas del dominio, por ejemplo, asociando un usuario a una acción específica.</li>
            </ol>
        </section>
        <section>
            <h1>Casos de uso:</h1>
            <article>
                <h5><strong>Caso de Uso 1: Registro de Usuario</strong></h5>
                <p><strong>Actor(es):</strong> Usuario</p>
                <p><strong>Descripción:</strong> El usuario se registra en el sistema proporcionando sus datos personales y credenciales.</p>
                <p><strong>Precondiciones:</strong></p>
                <ul>
                    <li>El usuario no debe estar registrado previamente.</li>
                    <li>El sistema debe estar disponible.</li>
                </ul>
                <p><strong>Flujo principal:</strong></p>
                <ol>
                    <li>El usuario accede a la página de registro.</li>
                    <li>El sistema solicita los datos personales (nombre, email, contraseña).</li>
                    <li>El usuario completa el formulario y lo envía.</li>
                    <li>El sistema valida los datos ingresados.</li>
                    <li>El sistema guarda los datos en la base de datos.</li>
                    <li>El sistema confirma el registro exitoso.</li>
                </ol>
                <p><strong>Postcondiciones:</strong> El usuario queda registrado en el sistema y puede iniciar sesión.</p>
            </article>
            <article>
                <h5><strong>Caso de Uso 2: Inicio de Sesión</strong></h5>
                <p><strong>Actor(es):</strong> Usuario</p>
                <p><strong>Descripción:</strong> El usuario inicia sesión en el sistema utilizando sus credenciales.</p>
                <p><strong>Precondiciones:</strong></p>
                <ul>
                    <li>El usuario debe estar registrado.</li>
                    <li>El sistema debe estar disponible.</li>
                </ul>
                <p><strong>Flujo principal:</strong></p>
                <ol>
                    <li>El usuario accede a la página de inicio de sesión.</li>
                    <li>El sistema solicita el email y la contraseña.</li>
                    <li>El usuario ingresa sus credenciales y las envía.</li>
                    <li>El sistema valida las credenciales.</li>
                    <li>El sistema permite el acceso al usuario.</li>
                </ol>
                <p><strong>Postcondiciones:</strong> El usuario accede al sistema con su cuenta.</p>
            </article>
            <article>
                <h5><strong>Caso de Uso 3: Solicitar Turno</strong></h5>
                <p><strong>Actor(es):</strong> Paciente</p>
                <p><strong>Descripción:</strong> El paciente solicita un turno para una fecha y hora específicas.</p>
                <p><strong>Precondiciones:</strong></p>
                <ul>
                    <li>El paciente debe estar registrado e iniciar sesión.</li>
                    <li>Deben existir turnos disponibles.</li>
                </ul>
                <p><strong>Flujo principal:</strong></p>
                <ol>
                    <li>El paciente accede a la sección de turnos.</li>
                    <li>El sistema muestra las fechas y horarios disponibles.</li>
                    <li>El paciente selecciona una fecha y hora.</li>
                    <li>El sistema valida la disponibilidad del turno.</li>
                    <li>El sistema guarda el turno en la base de datos.</li>
                    <li>El sistema confirma la reserva del turno.</li>
                </ol>
                <p><strong>Postcondiciones:</strong> El turno queda reservado para el paciente.</p>
            </article>
        </section>
        <section>
            <h1>Boceto Inicial del Diseño de Clases</h1>
            <img src="Clases.drawio.png" alt="Boceto del Diseño de Clases" width="600">
            <p>
                <a href="https://raw.githubusercontent.com/Sangona/SistemaGestionTurnos/main/Clases.drawio.png" target="_blank">
                    Ver imagen en línea
                </a>
            </p>
        </section>
    </main>
</body>
</html>