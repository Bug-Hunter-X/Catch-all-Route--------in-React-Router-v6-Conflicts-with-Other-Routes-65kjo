# React Router v6 Catch-all Route Conflict

This repository demonstrates a common issue with React Router v6 where a catch-all route (`/*`) unintentionally overrides other defined routes.

## Problem

When using a catch-all route in conjunction with other, more specific routes, the catch-all route may unexpectedly capture navigation even when a match for a more specific route exists.

## Solution

The solution involves careful route ordering and potentially using a more precise catch-all to avoid conflicts with the other path.