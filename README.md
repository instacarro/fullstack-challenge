# FullStack Challenge

Our FullStack challenge consists in trying to build a new system to schedule mechanical inspections for a vehicle such as a `car`. 

This system must has an admin area (authorization with e-mail and password) to manage and organize schedulings such as `Create`, `Update`, `Delete` and `List All` 
our employers must be able to see details about that mechanical inspection schedule. 

The `Owner entity`:
 - name
 - email

The `Vehicle entity`:
 - plate
 - make
 - model
 - year
 - Owner

The `Assessor entity`:
 - name
 - email
 - password

The `Schedule entity`:
 - date
 - Assessor
 - Vehicle

### Acceptance Criteria:
- Use TypeScript 
- FrontEnd (APP)
- Backend (API)
- Unit Tests
- Use `GitHub` to clone this repository and open a pull request following this pattern: `feature/your-full-goes-here`
- A `README.md` documenting how to run the project

### Optional and Plus
- Component Tests
- Try to make a container using `Docker` which builds a fresh and an usable image to deploy your project. 

### Questions
- Mail me `anderson.anzileiro@instacarro.com`
