<h1>Student Request & Issue Management Automation</h1>

  <p>
    This project is an end-to-end automation workflow built using <strong>n8n</strong> to manage
    and streamline student requests in a university environment. It is designed to simulate
    real-world college operations by handling request submission, routing, logging, and
    notifications in a structured and automated manner.
  </p>

  <h2>📌 Overview</h2>
  <p>
    Colleges and universities process multiple student requests daily, often resulting in
    manual effort and delays. This automation centralizes the request-handling process and
    ensures that submissions are properly categorized, routed to the correct department,
    logged systematically, and acknowledged automatically.
  </p>

  <h2>⚙️ Features</h2>
  <ul>
    <li><strong>Centralized Form Submission</strong> – Students submit complaints, leave requests,
        academic queries, and document requests through a single form.</li>
    <li><strong>Data Normalization</strong> – Incoming form data is cleaned and standardized
        for consistent processing.</li>
    <li><strong>Logic-Based Routing</strong> – Requests are routed based on request type,
        department, and priority level.</li>
    <li><strong>Department-wise Logging</strong> – All requests are stored in Google Sheets,
        organized by department for easy tracking.</li>
    <li><strong>Priority Handling</strong> – Urgent requests are escalated immediately,
        while normal requests follow the standard processing flow.</li>
    <li><strong>Automated Notifications</strong> – Confirmation emails are sent to students,
        with separate alerts for administrative staff.</li>
  </ul>

  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li>n8n – Workflow automation</li>
    <li>Google Sheets – Request logging and tracking</li>
    <li>Gmail – Email notifications</li>
  </ul>

  <h2>🧠 What This Project Demonstrates</h2>
  <ul>
    <li>End-to-end automation design using n8n</li>
    <li>Clean data handling and normalization</li>
    <li>Conditional routing with Switch and Set nodes</li>
    <li>Practical automation aligned with real institutional workflows</li>
  </ul>

  <h2>🚧 Project Status</h2>
  <p>
    <strong>This project is a prototype and not a final production-ready product.</strong>
    It is intended to demonstrate workflow design, automation logic, and real-world
    problem-solving using n8n. Additional security, validation, and scalability measures
    would be required for production use.
  </p>

  <h2>🚀 Future Enhancements</h2>
  <ul>
    <li>
      <strong>Status Tracking</strong> – Introduce request statuses such as
      <em>Pending</em>, <em>In Review</em>, <em>Approved</em>, or <em>Rejected</em>,
      with automated updates and notifications to students.
    </li>
    <li>
      <strong>Duplicate Request Detection</strong> – Identify and flag repeated or duplicate
      submissions from the same student to reduce misuse and administrative overhead.
    </li>
    <li>
      <strong>Optional AI-Based Summarization</strong> – Use AI to generate concise summaries
      of long requests for administrative review, with fallback logic to ensure the system
      functions without AI dependency.
    </li>
  </ul>

  <p>
    <em>This project is created for learning and demonstration purposes.</em>
  </p>
