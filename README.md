# miniature-fishstick
This repository serves as a learning resource for Git and GitHub, demonstrating various techniques used in a typical production setup. It includes two Postman collections: one for the common `thecatapi.com` and the other for the `GoalAPI` focused on tracking and managing goals.

## Postman Collections

### 1. thecatapi.com

#### Description

This collection interacts with `thecatapi.com`, a RESTful API providing random cat images. The primary purpose is to showcase basic API testing concepts.

#### Requests

1. **Get Random Cat**    
    - Endpoint: `/v1/images/search`
    - Purpose: Fetch a random cat image.
2. **Get Cat Categories**
    - Endpoint: `/v1/categories`
    - Purpose: Retrieve a list of cat image categories.
3. **Post Vote**
    - Endpoint: `/v1/votes`
    - Purpose: Submit a vote for a cat image, expressing user preference or feedback.
4. **Add to Favorites**
    - Endpoint: `/v1/favourites`
    - Purpose: Mark a specific cat image as a favorite, allowing users to curate a personalized collection.
5. **Remove from Favorites**
    - Endpoint: `/v1/favourites`
    - Purpose: Remove a cat image from the user's favorites list, providing the ability to manage saved content.

#### API Tested With

- **Tool**: Postman
#### Why thecatapi.com?

Who doesn't like some small cats [(especially in the basement)](https://www.youtube.com/watch?v=DZqz69e06uQ)?

### 2. GoalAPI

#### Description

This collection interacts with `GoalAPI`, a REST API designed for setting and tracking goals. It encompasses various functionalities related to managing goals, habits, milestones, and user profiles.

#### Requests

1. **Get Goals**
    
    - Endpoint: `/goals`
    - Purpose: Retrieve a list of all goals stored in the system, providing an overview of all active goals.
2. **Get Goals for User**
    
    - Endpoint: `/users/:username/goals`
    - Purpose: Fetch the goals associated with a specific user (identified by the username), enabling users to view and track their individual progress.
3. **Update Goal**
    
    - Endpoint: `/goals/:goal_id`
    - Purpose: Modify the details of a specific goal identified by its ID. This request allows users to update information such as due dates, progress, or any other goal-related attributes.
4. **Delete Goal**
    
    - Endpoint: `/goals/:goal_id`
    - Purpose: Delete a goal based on its unique ID. This operation is designed to remove a goal from the system when it is no longer relevant or applicable.
5. **Create Goal**
    
    - Endpoint: `/goals/:goal_id`
    - Purpose: Post a new goal based on its unique ID.

#### API Tested With

- **Tool**: Postman

#### Why GoalAPI?

- **Educational Value**: GoalAPI provides a practical example for testing more complex APIs with various functionalities, enhancing learning opportunities.
- **Diverse Endpoints**: The API includes different request types (create, update, delete, read), allowing users to practice diverse testing scenarios.
- **Real-world Relevance**: Mimicking a goal-tracking API reflects a common use case in real-world applications, making it beneficial for understanding practical testing scenarios.
