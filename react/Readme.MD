# React Application Upgrade Guide
Node 18 → Node 22

## Version Requirements
- **Previous Version:** Node 18
- **Current Version:** Node 22.14

## Migration Changes

### Node Environment Setup
```json
"engines": {
    "node": ">=22.14.0"
}
```

### ESLint Configuration
```json
"rules": {
    "no-unused-vars": "off"
}
```

### Dependencies Update
The following dependencies need to be updated:

| Package | Version |
|---------|---------|
| @testing-library/dom | ^10.0.0 |
| @testing-library/jest-dom | ^6.1.5 |
| @testing-library/react | ^16.2.0 |
| @testing-library/user-event | ^14.5.1 |
| web-vitals | ^4.2.4 |