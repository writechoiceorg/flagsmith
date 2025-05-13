---
id: intro
slug: /
title: Welcome to the Flagsmith Docs
sidebar_position: 1
sidebar_label: Overview
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import ThemedImage from '@theme/ThemedImage';
import Card from '@site/src/components/Card';
import CardHeader from '@site/src/components/Card/CardHeader';
import CardBody from '@site/src/components/Card/CardBody';
import CardFooter from '@site/src/components/Card/CardFooter';

# Feature Management Made Simple

[Flagsmith](https://flagsmith.com/) helps development teams release features with confidence. Our platform provides feature flags, remote config, and A/B testing capabilities across web, mobile, and server-side applications. Whether you're practicing trunk-based development, implementing progressive rollouts, or conducting experiments, Flagsmith has you covered.

:::tip Quick Start
🚀 Ready to dive in? [Follow our 5-minute quickstart guide](quickstart.md) to get up and running with Flagsmith!
:::

## Choose Your Path

<Tabs>
  <TabItem value="developer" label="🛠️ I'm a Developer" default>
    <Card>
      <CardHeader>
        <h3>Quick Integration Guide</h3>
      </CardHeader>
      <CardBody>
        <ul>
          <li>Set up your first feature flag in 5 minutes</li>
          <li>Integrate our SDKs into your application</li>
          <li>Implement feature flags in your code</li>
        </ul>
      </CardBody>
      <CardFooter>
        <a className="button button--primary button--sm" href="/quickstart">
          Start Integration
        </a>
      </CardFooter>
    </Card>
  </TabItem>
  <TabItem value="manager" label="👥 I'm a Product Manager">
    <Card>
      <CardHeader>
        <h3>Feature Management</h3>
      </CardHeader>
      <CardBody>
        <ul>
          <li>Learn about A/B testing</li>
          <li>Set up user segments</li>
          <li>Manage feature rollouts</li>
        </ul>
      </CardBody>
      <CardFooter>
        <a className="button button--primary button--sm" href="/advanced-use/ab-testing">
          Explore Features
        </a>
      </CardFooter>
    </Card>
  </TabItem>
  <TabItem value="admin" label="🔧 I'm a System Admin">
    <Card>
      <CardHeader>
        <h3>Deployment Options</h3>
      </CardHeader>
      <CardBody>
        <ul>
          <li>Self-hosted deployment guide</li>
          <li>Enterprise features</li>
          <li>Security & compliance</li>
        </ul>
      </CardBody>
      <CardFooter>
        <a className="button button--primary button--sm" href="/deployment">
          View Deployment Options
        </a>
      </CardFooter>
    </Card>
  </TabItem>
</Tabs>

## Popular SDKs

<div className="row">
  <div className="col col--4">
    <Card>
      <CardHeader>
        <h3>Frontend</h3>
      </CardHeader>
      <CardBody>
        <ul>
          <li><a href="/clients/javascript">JavaScript</a></li>
          <li><a href="/clients/react">React</a></li>
          <li><a href="/clients/next-ssr">Next.js</a></li>
        </ul>
      </CardBody>
    </Card>
  </div>
  <div className="col col--4">
    <Card>
      <CardHeader>
        <h3>Mobile</h3>
      </CardHeader>
      <CardBody>
        <ul>
          <li><a href="/clients/ios">iOS/Swift</a></li>
          <li><a href="/clients/android">Android/Kotlin</a></li>
          <li><a href="/clients/flutter">Flutter</a></li>
        </ul>
      </CardBody>
    </Card>
  </div>
  <div className="col col--4">
    <Card>
      <CardHeader>
        <h3>Backend</h3>
      </CardHeader>
      <CardBody>
        <ul>
          <li><a href="/clients/server-side?language=python">Python</a></li>
          <li><a href="/clients/server-side?language=nodejs">Node.js</a></li>
          <li><a href="/clients/server-side?language=java">Java</a></li>
        </ul>
      </CardBody>
    </Card>
  </div>
</div>

## Key Features

<div className="row">
  <div className="col col--6">
    <Card>
      <CardHeader>
        <h3>🎯 Feature Flags</h3>
      </CardHeader>
      <CardBody>
        Control feature rollouts, conduct A/B tests, and manage technical debt with our powerful feature flagging system.
      </CardBody>
      <CardFooter>
        <a href="/basic-features/managing-features">Learn more →</a>
      </CardFooter>
    </Card>
  </div>
  <div className="col col--6">
    <Card>
      <CardHeader>
        <h3>🌐 Edge API</h3>
      </CardHeader>
      <CardBody>
        Get lightning-fast response times with our globally distributed Edge API network.
      </CardBody>
      <CardFooter>
        <a href="/advanced-use/edge-api">Learn more →</a>
      </CardFooter>
    </Card>
  </div>
</div>

:::note Want to host Flagsmith yourself?
Flagsmith is open source! Check out our [deployment options](version-comparison.md) to learn more about self-hosting vs SaaS.
:::
