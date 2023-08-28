# User Stories

User Story 1:
As a user, I want to create a new account using my email and password so that I can start using the social media platform.

Feature Tasks:
- Design and implement a registration form
- Set up email verification process
- Create a secure password storage mechanism
- Develop error handling for invalid inputs
- Store user account information in the database

Acceptance Tests:
- Verify that users receive a verification email upon registration
- Test account creation with valid and invalid inputs
- Ensure passwords are securely stored and hashed
- Check that user account details are correctly stored in the database

Estimated Size: Small

User Story 2:
As a user, I want to post text updates on my profile so that I can share my thoughts and activities with my friends.

Feature Tasks:
- Design a post composition interface
- Implement text input and formatting options
- Enable posting to the user's profile
- Add real-time updating of the user's feed
- Implement privacy settings for posts

Acceptance Tests:
- Test posting with various text lengths and formats
- Verify that posts appear on the user's profile and followers' feeds
- Check that privacy settings restrict post visibility as intended

Estimated Size: Small

User Story 3:
As a user, I want to follow other users' profiles so that I can stay updated on their posts and activities.

Feature Tasks:
- Design a user profile interface
- Implement a "Follow" button on user profiles
- Develop a system for tracking followers and following
- Add a feed displaying posts from followed users

Acceptance Tests:
- Test following and unfollowing different profiles
- Verify that the follower/following counts update correctly
- Check that the user's feed displays posts from followed users

Estimated Size: Small

User Story 4:
As a user, I want to upload images to my posts so that I can share visual content with my friends.

Feature Tasks:
- Enhance the post composition interface to support image uploads
- Implement image upload and storage mechanisms
- Ensure images are properly compressed and optimized
- Display uploaded images within posts and on user profiles

Acceptance Tests:
- Test image upload with various image formats and sizes
- Verify that uploaded images are displayed correctly in posts
- Check that images do not affect the platform's performance negatively

Estimated Size: Medium

User Story 5:
As a user, I want to like and comment on posts made by other users so that I can engage with their content.

Feature Tasks:
- Add "Like" and "Comment" buttons to posts
- Implement the ability to like and unlike posts
- Enable users to write and post comments on others' posts
- Display likes and comments counts on posts

Acceptance Tests:
- Test liking and unliking posts
- Verify that comments can be added, edited, and deleted
- Check that likes and comments counts accurately reflect user interactions

Estimated Size: Small

Remember, these user stories are just a starting point. As your project progresses, you may need to refine, expand, or reprioritize them based on feedback and changing requirements. Each user story should represent a discrete piece of functionality that can be developed, tested, and deployed independently.


# Software Requirements
## Vision

The vision of our social media platform is to provide users with a dynamic and engaging online space where they can connect, share their thoughts, experiences, and creative content with their friends and followers. This project aims to address the need for a platform that fosters meaningful interactions, facilitates content sharing, and promotes positive engagement among users.

## Pain Point

Our project solves the pain point of users feeling disconnected and overwhelmed on existing social media platforms. Many users find it challenging to filter through irrelevant content and maintain genuine connections. Our platform strives to create a more personal and focused social experience, where users can engage with content that matters to them and foster authentic relationships.

## Why Care

In today's digital age, social media has become a central part of our lives. However, the current platforms often prioritize quantity over quality of interactions. Our product offers a fresh perspective by prioritizing meaningful connections, relevant content, and a user-friendly experience. By addressing the drawbacks of existing platforms, we aim to provide users with a space where they can truly connect and engage.

## Scope (In/Out)

### IN - What Our Product Will Do

1. **User Profiles:** Users can create profiles, including profile pictures and personal information.
2. **Content Sharing:** Users can create and post text, images, and videos to share with their followers.
3. **Interactions:** Users can like, comment, and share posts created by others.
4. **Friend/Follow System:** Users can follow and befriend other users to see their posts in their feed.

### OUT - What Our Product Will Not Do

1. **Messaging Platform:** Our product will not have a dedicated messaging feature for private conversations.
2. **E-commerce Integration:** Our product will not facilitate direct sales of products within the platform.

## Minimum Viable Product (MVP) vs. Stretch Goals

**MVP Functionality:**

1. User Profiles and Authentication
2. Content Sharing (Text and Images)
3. Interactions (Likes and Comments)
4. Friend/Follow System

**Stretch Goals:**

1. Video Content Sharing
2. Advanced Privacy Settings
3. Analytics Dashboard for Users

## Functional Requirements

1. **User Account Management:**
	- An admin can create and delete user accounts.
	- Users can update their profile information.

2. **Content Creation and Interaction:**
	- Users can create and post text updates with optional images.
	- Users can like and comment on posts created by other users.
	- Users can follow other users to see their posts in their feed.

## Data Flow

1. User logs in or signs up.
2. User creates a post (text with optional image).
3. User's post is displayed in their profile and followers' feeds.
4. Other users can like and comment on the post.

## Non-Functional Requirements

1. **Security:**
	Our platform will implement industry-standard encryption protocols for data transmission and storage to ensure the privacy and security of user information and interactions. User passwords will be securely hashed and salted before storage.

2. **Usability:**
	Our platform will prioritize user-friendly design, intuitive navigation, and responsive layout to ensure a seamless and enjoyable user experience. User feedback and usability testing will be conducted to continuously improve the platform's usability.

# Domain Modeling

