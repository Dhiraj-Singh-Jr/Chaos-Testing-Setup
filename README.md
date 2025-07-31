# Chaos Engineering Test Suite

## Introduction

Modern internet companies operate on complex infrastructures tailored to their specific needs. While documentation may guarantee system reliability, real-world resilience is proven only through practical testing. This is where **Chaos Engineering** comes in—a discipline pioneered by Netflix after facing critical outages in production.

Chaos Engineering involves deliberately injecting failures into a system—such as shutting down pods, simulating DDoS attacks, overloading databases, or spiking traffic—to observe how it behaves under stress. The goal is to uncover hidden weaknesses and ensure the system can gracefully recover from unexpected disruptions.

However, it's important to note that Chaos Engineering isn't suitable for every company. For early-stage infrastructures with minimal complexity or predictable traffic, such tests may offer little value. Moreover, before running chaos experiments, teams must first understand their system’s baseline behavior under various load conditions—low, medium, and peak. Only then can failures be meaningfully simulated and analyzed.

This project implements a **Chaos Testing setup** that targets specific services to validate their fault tolerance and recovery mechanisms, inspired by real-world use cases.[PagerDuty – What is Chaos Testing?](https://www.pagerduty.com/resources/engineering/learn/what-is-chaos-testing/)
