graph TD;
    A[Create Repository] --> B[Add Files];
    B --> C[Stage Changes];
    C --> D[Commit Changes];
    D --> E[Push to Remote Repository];
    E --> F{Pull Request};
    F --> |Accepted| G[Merge Changes];
    F --> |Rejected| C;
