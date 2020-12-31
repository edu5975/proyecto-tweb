﻿# proyecto-tweb
Rutas

Rutas para las alergias
    /alergias (get, post)
    /alergias/:id (get, put, delete)

Rutas para las enfermedades
    /enfermedades (get, post)
    /enfermedades/:id (get, put, delete)

Rutas para las especialidades
    /especialidades (get, post)
    /especialidades/:id (get, put, delete)

Rutas para las cirugias
    /cirugias (get, post)
    /cirugias/:id (get, put, delete)

Rutas para los pacientes
    /pacientes (get, post)
    /pacientes/:id (get, put, delete) 

Rutas para pacientes_enfermedades
    /pacientes/:id/enfermedades (get)
    /pacientes/:idPacientes/enfermedades/:idEnfermedades (get, post, delete)

Rutas para pacientes_alergias
    /pacientes/:id/alergias (get)
    /pacientes/:idPacientes/alergias/:idAlergias (get, post, delete)

Rutas para pacientes_cirugias
    /pacientes/:id/cirugias (get)
    /pacientes/:idPacientes/cirugias/:idCirugias (get, post, delete)

Rutas para los servicios
    /servicios (get, post)
    /servicios/:id (get, put, delete)

Rutas para los medicos
    /medicos (get, post) 
    /medicos/:id (get, put, delete)

Rutas para servicios_medicos
    /medicos/:id/servicios (get)
    /medicos/:idMedicos/servicios/:idServicios (get, post, delete)

Rutas para consultas
    /consultas (get)
    /consultas/:id (get, delete)
    /pacientes/:idPacientes/consultas (get, post)
    /pacientes/:idPacientes/consultas/:idConsultas (get, put, delete)

Rutas para covid
    /covid (get, post)
    /covid/:id (get, delete)
    /pacientes/:id/covid (get)
    /medicos/:id/covid (get)

Rutas para recetas
    /recetas (get)
    /recetas/:id (get, delete)
    /consultas/:idConsulta/recetas (get)
    /consultas/:idConsulta/recetas/:idRecetas (get, put, delete)
