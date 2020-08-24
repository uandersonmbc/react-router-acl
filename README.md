```javascript
const authorizedRoutes = [
  {
    path: "/dashboard/analysis/realtime",
    exact: true,
    permissions: ["admin", "user"],
    redirect: "/login",
    component: WorkInProgress,
  },
];
```
