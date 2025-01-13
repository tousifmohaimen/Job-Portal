<h1>Job Portal</h1>
  <p>
    A responsive job portal that connects job seekers and employers, built using
    <strong>HTML</strong>, <strong>CSS</strong>, <strong>JavaScript</strong>, <strong>PHP</strong>, and <strong>MySQL</strong>.
  </p>

  <h2>Features</h2>
  <h3>For Job Seekers:</h3>
  <ul>
    <li>Create and manage profiles</li>
    <li>Browse and search for job listings</li>
    <li>Apply for jobs online</li>
    <li>Track application status</li>
  </ul>

  <h3>For Employers:</h3>
  <ul>
    <li>Register and manage company profiles</li>
    <li>Post job openings</li>
    <li>Review job applications</li>
    <li>Contact shortlisted candidates</li>
  </ul>

  <h3>Admin Panel:</h3>
  <ul>
    <li>Manage users (job seekers and employers)</li>
    <li>Monitor job postings and applications</li>
    <li>Perform CRUD operations on data</li>
  </ul>

  <h2>Tech Stack</h2>
  <ul>
    <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
    <li><strong>Backend:</strong> PHP</li>
    <li><strong>Database:</strong> MySQL</li>
  </ul>

  <h2>Installation</h2>
  <ol>
    <li><strong>Clone the Repository</strong>
      <pre>
        <code>git clone https://github.com/tousifmohaimen/Job-Portal.git
cd job-portal</code>
      </pre>
    </li>
    <li><strong>Set Up the Database</strong>
      <ul>
        <li>Import the SQL file (<code>job_portal.sql</code>) into your MySQL database.</li>
        <li>Update the database connection details in <code>config.php</code>:
          <pre>
            <code>
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "job_portal";
            </code>
          </pre>
        </li>
      </ul>
    </li>
    <li><strong>Configure the Project</strong>
      <ul>
        <li>Ensure your server supports PHP and MySQL.</li>
        <li>Place the project in the web server's root directory (e.g., <code>htdocs</code> for XAMPP).</li>
      </ul>
    </li>
    <li><strong>Run the Application</strong>
      <ul>
        <li>Start your server (e.g., XAMPP or WAMP).</li>
        <li>Access the portal at <code>http://localhost/job-portal</code>.</li>
      </ul>
    </li>
  </ol>
