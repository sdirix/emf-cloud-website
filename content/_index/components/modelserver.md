+++
title = "The model server"
weight = 20

[asset]
  icon = "fas fa-database"
  url = "https://github.com/eclipsesource/modelserver"
+++

The existing EMF implementation already supports loading, model manipulation, and serialisation out-of-the-box. The <a href="https://github.com/eclipsesource/modelserver">EMF.cloud model server</a> adds a facade on top of existing technologies to connect web-based clients. It manages the runtime state of loaded models (“shared editing domain”). It allows applying changes using a command pattern and and register for changes. Finally, it provides a Java and JavaScript REST API including multiple formats (JSON or XMI).
