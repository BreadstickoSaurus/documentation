# Collection platform
---

## General Idea
The general idea of this project is a collection platform for games in this case. It is described how difficult it is to change in the `changeType.md` file.
In this project, you can create an account and start creating your collection or wishlist of games. This can be useful for many things like:
- Knowing what you have when buying new things
- Knowing what you want when buying new things
- Showing your collection/wishlist to others easily.

You can allow people to view your collection/wishlist for future use. This way, when you see, let's say, a game at a garage sale, you can quickly check if they want it or already have it.

In `todoList.md` you have a quick overview of what is available in the project.

## Backend
For this part of the project, we have used Deno as a runtime environment, for its standard TypeScript and ease of use.
The project structure is as follows:
- endpoint
- controller
- repository / model

The backend has all required endpoints needed to run the frontend without problems. All of the endpoints have checks in place to verify if all the input data is correct and provide an appropriate response in case of a problem.

For more info:
- https://gitlab.ti.howest.be/ti/2024-2025/s5/project-iv/projecten/project-01/code/backend

### Database
We have used a regular SQL database for the project with scripts that create everything needed to run the project.

For more info:
- https://gitlab.ti.howest.be/ti/2024-2025/s5/project-iv/projecten/project-01/code/data

## Frontend
For the frontend of this project, we have used Vue.js as our framework, because it is easy to use and quick to set up. In here, everything as requested by the client is available.
Some of its main features are:
- Semantic search
- Viewing, adding, removing, updating on collection/wishlist
- Follow other people without the need of an account

The project is set up with a router, multiple views that have components, and uses services.

For more info:
- https://gitlab.ti.howest.be/ti/2024-2025/s5/project-iv/projecten/project-01/code/frontend

## Docker
We have created a Docker Compose file with 3 Docker files so the project can be easily set up using `docker compose up`. All the required projects (backend, frontend, database) are set up with this and have seeders included with test data.

For more info:
- https://gitlab.ti.howest.be/ti/2024-2025/s5/project-iv/projecten/project-01/docker