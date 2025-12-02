# CEOofNothing_SolanaBootcamp

CEOofNothing is transforming into a CEOofSomething, so she is learning Solana development. 

This Readme serves as a record of her progress through Solana's Blockchain Developer Bootcamp:
 - YouTube: https://youtu.be/amAq-WHAFs8?si=yXr4HZWtEj9Qssab
 - Github: https://github.com/solana-developers/developer-bootcamp-2024


## 24 November 2025 Achievements: 
1. Deployed Favorites program to Devnet:
   - Program: 2sijG8W6LryZCM138e6eDL5ncr1QyxKtWKHYp9NVD58J
   - TX: https://explorer.solana.com/tx/ie1QmZJYWmUcPi4uUWPQLSsn1eMZm4RrsQLeuXJed554JaMsWvK4pT6JvKHxeprpxQdAwpbYXrVGnmijx2JdKLZ?cluster=devnet
2. Wrote to the program successfully:
   - TX: https://explorer.solana.com/tx/2sbfvEqUc6Qv4QwUCaH9RKJFugMNPB54ViHBPfMWJRCfU89n8dVhfAkrWESGgdNMKeR7aUZUWikfrexFe4mxtqU5?cluster=devnet
   - New PDA created sucessfully: BMY74rhLrqEwkPzhz8fCcScHqXrEA81uhg2umEa3nnZk (for user: BAcC7NDTSmDgR84suzA3UDCobtEPx8YtJpkmycMKhRcC)
   - 😩 Found a bug in the instructions log, oh noooos!
   - [bug in instructions log](image.png)
3. Resolved the bug by correcting syntax in the program.
4. Upgraded the program:
   - https://explorer.solana.com/tx/5xTFhvJJr2a3QJ3gKpmMH9HAiPCsfAFocX1CB75byip54Awa5FiBBSMjaWVEzWKHWgDSdzZojtP6u3ZY8rm5LX2a?cluster=devnet
5. Wrote to the program again, this time seeing the expected result! 
   - https://explorer.solana.com/tx/5xaxfTC28VKY3L3XfvHQdkXM4dbTug46hXeeHhRQKRwEEkdCEd79iE4iVdqkK5QnbJdDjNrDyBxzqYafuj4Yk6L3?cluster=devnet
   - Same PDA as before: BMY74rhLrqEwkPzhz8fCcScHqXrEA81uhg2umEa3nnZk
   ![successful write to program](image-1.png)
6. Attempted to write to the program with new keys, but using previous user's PDA. It failed as expected. 
7. 💃 Did a happy dance.

---------------------------------------------------

## 2 December 2025 Achievements

**Summary**: Began Project 2, Creating a Voting Application!

1. Set up local environment by installing or creating the following: 
    - Rust
    - Solana CLI
    - Anchor (used Anchor Version Manager (AVM))
    - NPM
    - A venv (not sure if helpful for Solana): /Users/--/venvs
    - A Custom Terminal profile: Solana
        * Activates the venv
        * Navigates to my SolanaBootcamp folder (Github repo)

    - Project folder: /Users/--/Documents/GitHub/CEOofNothing_SolanaBootcamp/voting
2. Set up the project: 
   - /Users/--/Documents/GitHub/CEOofNothing_SolanaBootcamp/voting/voting-dapp
   - Launched app:
   ```bash
    cd voting/voting-dapp
    npm run dev
    ```
   - open http://localhost:3000 in browser
3. That's enough for today!
   - Pickup later here: [Solana Developer Bootcamp 2024 - Learn Blockchain and Full Stack Web3 Development - Projects 1-9 | TS 46:17](https://youtu.be/amAq-WHAFs8?si=4e8Z4x5blb0FHcAJ&t=2777)


References: 
[Anchor Docs | Installation](https://www.anchor-lang.com/docs/installation)
[Solana Docs | Install Dependencies](https://solana.com/docs/intro/installation/dependencies)
[Solana Developers | Developer Bootcamp 2024 | Project 2: Voting Application](https://github.com/solana-developers/developer-bootcamp-2024/tree/main/project-2-voting)