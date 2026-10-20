PHP/MySQL API foundation
------------------------
This UI is ready to connect to PHP endpoints. Recommended endpoints:
POST /api/login.php
GET/POST /api/projects.php
GET/POST /api/datasets.php
GET/POST /api/reports.php
POST /api/analysis.php
Use PDO prepared statements, password_hash/password_verify, CSRF protection, MIME/size validation for uploads, role-based authorization and audit logging.
For production statistical regression, connect analysis.php to a Python/R analysis service or a tested PHP statistics library.
