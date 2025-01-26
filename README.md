Week 1: MongoDB Fundamentals Assignment

**Objective:**
- Apply MongoDB concepts learned throughout the week.
- Practice database creation, CRUD operations, and aggregation queries.

**Instructions:**
1. **Setup MongoDB:**
   - Install MongoDB locally or create a cloud database using MongoDB Atlas.
   - Create a new database named `student_management`.

2. **Project Structure:**
   - Create a GitHub repository linked to GitHub Classroom.
   - Organize your files as follows:
     ```
     student_management/
     │-- scripts/
     │    ├── createDatabase.js
     │    ├── insertData.js
     │    ├── fetchData.js
     └── README.md
     ```

3. **Documentation:**
   - Provide a clear `README.md` with step-by-step setup and usage instructions.
   - Include explanations of the implemented CRUD operations and aggregation queries.

**Tasks:**
1. **Database Creation:**
   - Create a `student_management` database with the following collections:
     - `students` (fields: `name`, `age`, `class`, `subjects` [array])
     - `teachers` (fields: `name`, `subject`, `yearsOfExperience`)
     - `courses` (fields: `title`, `description`, `teacherId` [reference])

2. **CRUD Operations:**
   - Implement the following:
     - Add new students, teachers, and courses.
     - Retrieve student details based on class.
     - Update a teacher’s years of experience.
     - Delete a course by title.

3. **Aggregation Queries:**
   - Write queries to:
     - Find students by course.
     - Count teachers per subject.
     - Calculate the average student age.

4. **Submission:**
   - Commit all scripts and the `README.md` to your GitHub repository.

**Evaluation Criteria:**
- Proper database structure and schema design.
- Correct implementation of CRUD operations.
- Functional aggregation queries.
- Clear and concise documentation.
- Proper usage of GitHub for version control.

**Deadline:** Submit by [insert deadline date].

