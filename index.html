<%@ page import="java.sql.*" %>
<%@ page contentType="text/html;charset=UTF-8" language="java" %>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inventario de Zapatos</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <!-- Barra de navegación -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Inventario de Zapatos</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Listado de Zapatos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Agregar Zapato</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Eliminar Zapato</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Editar Zapato</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Contenido principal -->
    <div class="container my-4">
        <h1 class="text-center">Bienvenido al Inventario de Zapatos</h1>
        <p class="text-center">Aquí puedes gestionar el inventario de zapatos con las opciones de listado, agregar, eliminar y editar.</p>
        
        <!-- Tabla de ejemplo para el listado de zapatos -->
        <div class="table-responsive">
            <table class="table table-striped table-bordered">
                <thead class="table-dark">
                    <tr>
                        <th>ID</th>
                        <th>Modelo</th>
                        <th>Marca</th>
                        <th>Talle</th>
                        <th>Color</th>
                        <th>Precio Costo</th>
                        <th>Precio Venta</th>
                        <th>Cantidad</th>
                        <th>Acciones</th>
                    </tr>
                </thead>
                <tbody>
                    <%
                        // Conectar a la base de datos y obtener la lista de zapatos
                        Connection conn = null;
                        PreparedStatement ps = null;
                        ResultSet rs = null;

                        try {
                            // Configuración de la conexión
                            Class.forName("com.mysql.cj.jdbc.Driver");
                            conn = DriverManager.getConnection("jdbc:mysql://localhost:3306/zapateria", "root", "");

                            // Consulta para obtener todos los zapatos
                            String sql = "SELECT * FROM zapatos";
                            ps = conn.prepareStatement(sql);
                            rs = ps.executeQuery();

                            // Iterar sobre el resultado de la consulta y mostrar en la tabla
                            while (rs.next()) {
                                int id = rs.getInt("id");
                                String modelo = rs.getString("modelo");
                                String marca = rs.getString("marca");
                                int talle = rs.getInt("talle");
                                String color = rs.getString("color");
                                double precioCosto = rs.getDouble("precio_costo");
                                double precioVenta = rs.getDouble("precio_venta");
                                int cantidad = rs.getInt("cantidad");
                    %>
                                <tr>
                                    <td><%= id %></td>
                                    <td><%= modelo %></td>
                                    <td><%= marca %></td>
                                    <td><%= talle %></td>
                                    <td><%= color %></td>
                                    <td><%= precioCosto %></td>
                                    <td><%= precioVenta %></td>
                                    <td><%= cantidad %></td>
                                    <td>
                                        <a href="editarZapato.jsp?id=<%= id %>" class="btn btn-primary btn-sm">Editar</a>
                                        <a href="eliminarZapato.jsp?id=<%= id %>" class="btn btn-danger btn-sm">Eliminar</a>
                                    </td>
                                </tr>
                    <%
                            }
                        } catch (Exception e) {
                            e.printStackTrace();
                        } finally {
                            if (rs != null) rs.close();
                            if (ps != null) ps.close();
                            if (conn != null) conn.close();
                        }
                    %>
                </tbody>
            </table>
        </div>

        <!-- Botón para agregar un nuevo zapato -->
        <div class="d-flex justify-content-end">
            <a href="insertarZapato.jsp" class="btn btn-success mt-3">Agregar Nuevo Zapato</a>
        </div>
    </div>

    <!-- Bootstrap JS y dependencias -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"></script>
</body>
</html>
