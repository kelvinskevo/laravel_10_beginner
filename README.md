# Laravel 10 Course

## Project Idea

1. User can create a new help ticket
2. Admin can reply on ticket
3. Admin can reject or resolve ticket
4. Notification status via email wehn admin updates ticket
5. User can give ticket title and description
6. User can upload a document like pdf or image

## Table Structure

1. Tickets

    - title(string) {required}

    - description(text) {required}

    - status(open {required}, resolved, rejected),

    - attachment(string) {nullable}

    - user_id {filled by laravel}

    - status_changed_by_id {nullable}

2. Replies

    - body(text) {required}

    - user_id {filled by laravel}

    - ticket_id {filled by laravel}
