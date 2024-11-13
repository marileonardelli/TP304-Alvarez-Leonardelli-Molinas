# NanoGenTech

### Integrantes
46924 - Alvarez Sol Micaela <br>
51337 - Leonardelli Marianela <br>
47786 - Molinas María del Rosario

### Link Front y Back End
https://github.com/rosariomolinas/FrontEnd <br>
https://github.com/rosariomolinas/BackEnd

### Link Modelo Dominio
https://drive.google.com/file/d/17oPDkYYfvcBED89_CynL1rDIaq_Wg-zL/view?usp=sharing

### Descripción
NanoGenTech es la nueva tecnología de Indigo que se encarga de presupuestar y agendar exploraciones médicas en pacientes humanos, así como también reservar y visualizar sus turnos en el quirofano.
El profesional utiliza esta herramienta para realizar los estudios que el paciente necesita, trazar la ruta de mayor eficiencia de un órgano a otro, en caso de necesitarlo y obtener el costo total final.
El paciente, por otro lado, puede visualizar su turno y en caso de algun imprevisto, cancelarlo o solicitar reprogramarlo.



### Regularidad
CRUD simple: <br>
1.Pacientes: <br>
Create: registrar nuevo paciente con su información personal (nombre, apellido, edad).<br>
Read: muestra la información del paciente.<br>
Update: modificar la información del paciente.<br>
Delete: eliminar el perfil del paciente en caso de que sea necesario.<br><br>

2.Organos:<br>
Create: registrar nuevo organo con los tratamientos y medicaciones que admite (codorgano, descripcion, tratamientos,medicacion)<br>
Read: muestra la información del organo.<br>
Update: modificar la información del organo.<br>
Delete: eliminar el organo en caso de que sea necesario.<br><br>

3.Intervencion:<br>
Create: programar nuevos turnos para internvenciones, asignando fecha, paciente, medico, organos, sus tratamientos correspondientes y calculando el costo y el tiempo.<br>
Read: visualizar las intervenciones programadas.<br>
Update: modificar detalles de los turnos (fecha, medico, organos que seran intervenidos).<br>
Delete: cancelar intervencion.<br><br>

4.Médico:<br>
Create: registrar nuevo médico con su información personal (número de matrícula, nombre, apellido).<br>
Read: muestra la información del médico.<br>
Update: modificar la información del médico.<br>
Delete: eliminar el perfil del médico en caso de que sea necesario.<br><br>

CRUD dependiente:<br>
1.CRUD Intervencion {depende de} CRUD Paciente <br>
1.CRUD Intervencion {depende de} CRUD Medico<br><br>

Listado + detalle:<br>
1.Listado de pacientes, activos, inactivos y ambos<br>
2.Listado de intervenciones filtrado por médico que la realiza o paciente intervenido<br><br>

CUU:<br>
1.Reservar turno para intervencion.<br>
2.Presupuestar intervencion.<br>
