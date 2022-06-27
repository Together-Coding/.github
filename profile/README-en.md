# Together Coding

[English](#together-coding) ∙ [한국어](/profile/README.md)

This project was a capstone project of the Department of Computer Science, and was carried out by [a2tt](https://github.com/a2tt), [boyfromthewell](https://github.com/boyfromthewell) and [chasw0326](https://github.com/chasw0326) from March 13 to June 15. *Together Coding* is a **Real-Time Code Sharing Service** for one-to-many coding classes.

We aimed to create a service that can remedy for the shortcomings of existing collaborative code sharing services and traditional coding classes.

## Major Features

All users can do:

- To create courses and lessons, and to manage participating students.
- To create, read, modify, and delete files like a typical code editor.
- To share changes to files and cursor positions with others in real-time.
- To execute code through an external server.
- To create QnA referencing code.

## Expected Effects

- Teachers can manage the code sharing systematically and continuously for each lesson.
- Every participant has their own project on the AWS cloud.
- This service improves the unidirectional nature of existing lessons by sharing the code modification in real-time.
- Participants can ask and answer questions more efficiently and intuitively through code-referencing QnA.
- Teachers can accumulate and record the current status of the students.
- Even after the sharing terminated, participants can always access the code that has been used during the lesson.

## Repositories

- [Client](https://github.com/Together-Coding/Client) : Pages to manage lessons and Web IDE
- [API-Server](https://github.com/Together-Coding/API-Server) : User, Authentication and Lesson related API
- [Runtime-Container](https://github.com/Together-Coding/Runtime-Container) : Docker images where code can be executed
- [Runtime-Agent](https://github.com/Together-Coding/Runtime-Agent) : SSH relay and managing its container in *Runtime-Container*
- [Runtime-Bridge](https://github.com/Together-Coding/Runtime-Bridge) : Allocation of *Runtime-Container* to users
- [IDE-Server](https://github.com/Together-Coding/IDE-Server) : Websocket server processing all real-time events from IDE.
- [Project-Backup-Lambda](https://github.com/Together-Coding/Project-Backup-Lambda) : Migration of old projects from Redis to AWS S3
- [Performance-Analysis](https://github.com/Together-Coding/Performance-Analysis) : Performance analysis for *IDE-server*

## Related Links

- [Presentation](https://bit.ly/3zN9h7b)
- [Demo video](https://youtu.be/OmvaW_u2occ)
