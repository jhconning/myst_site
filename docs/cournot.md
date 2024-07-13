---
modified: 2024-06-25T19:43:48.776Z
title: "Cournot Competition: The Strategic Dance of Oligopolies"
export: pdf
---

# Cournot Competition: The Strategic Dance of Oligopolies

## Introduction to Cournot Competition

Cournot competition is a model of oligopoly behavior where:
- Firms compete on quantity, not price
- Each firm chooses output independently
- Developed by Antoine Augustin Cournot in 1838

## Key Assumptions of the Cournot Model

- Homogeneous product
- Fixed number of firms (typically two)
- Firms make output decisions simultaneously
- No collusion between firms
- Firms have perfect information
- Barriers to entry exist

## The Cournot Equilibrium

### How Firms Decide

1. Firms maximize profit given competitors' output
2. Each firm's best response depends on others
3. Equilibrium: no firm wants to change output

### The Math

Let's consider a duopoly where two firms produce a homogeneous product. The inverse demand function is given by:

```{math}
P = a - bQ
```

where $P$ is the market price, $Q$ is the total market output, and $a$ and $b$ are positive constants.

The total market output is the sum of the outputs of both firms:

```{math}
Q = q_1 + q_2
```

Each firm's profit function is:

```{math}
\pi_i = P(Q)q_i - C(q_i)
```

where $C(q_i)$ is the cost function for firm $i$.

Assuming constant marginal cost $c$, the profit function becomes:

```{math}
\pi_i = (a - b(q_1 + q_2))q_i - cq_i
```

To find the Cournot-Nash equilibrium, each firm maximizes its profit by setting the derivative of its profit function with respect to its output equal to zero:

```{math}
\frac{d\pi_1}{dq_1} = a - 2bq_1 - bq_2 - c = 0
```

```{math}
\frac{d\pi_2}{dq_2} = a - 2bq_2 - bq_1 - c = 0
```

Solving these equations simultaneously gives us the Cournot-Nash equilibrium quantities:

```{math}
q_1^* = q_2^* = \frac{a-c}{3b}
```

The equilibrium price is:

```{math}
P^* = a - b(q_1^* + q_2^*) = \frac{a + 2c}{3}
```

### The Graph

[A graph showing two reaction functions intersecting. The x-axis represents Firm 1's output, the y-axis Firm 2's output. The intersection point is labeled as the Cournot-Nash equilibrium.]

- Reaction functions show best response to competitor
- Intersection point is the Cournot-Nash equilibrium
- Neither firm has incentive to deviate unilaterally

## Characteristics of Cournot Competition

### Market Outcomes

- Price above marginal cost $(P > MC)$
- Output below perfectly competitive level
- Positive profits in short and long run

### Market Power

- Firms have some market power
- Lerner Index: $\frac{P - MC}{P} > 0$
- Market power decreases with more firms

In a Cournot oligopoly with $n$ firms, the Lerner Index can be expressed as:

```{math}
\frac{P - MC}{P} = \frac{1}{n\epsilon}
```

where $\epsilon$ is the market demand elasticity.

## Real-World Applications

1. Oil production (OPEC countries)
2. Airline industry on specific routes
3. Smartphone operating systems (Android vs iOS)

## Limitations of the Cournot Model

- Assumes quantity as strategic variable
- No dynamic interaction between firms
- Ignores potential for collusion
- Simplified assumptions may not hold in reality

## Conclusion and Key Takeaways

- Cournot competition models oligopoly behavior
- Firms compete on quantity, reaching a Nash equilibrium
- Results in outcomes between perfect competition and monopoly
- Provides insights into real-world oligopolistic markets
- Forms foundation for more complex oligopoly models

## Discussion Questions

1. How might the Cournot equilibrium change if firms could make sequential rather than simultaneous decisions?

2. In what ways might firms in a Cournot oligopoly be incentivized to collude, and what factors might prevent collusion?

3. How do you think the rise of big data and AI might impact firms' ability to compete in a Cournot-like fashion?

```

