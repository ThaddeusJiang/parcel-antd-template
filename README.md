# Parcel AntD Template
[![Build Status](https://travis-ci.org/ThaddeusJiang/parcel-antd-template.svg?branch=master)](https://travis-ci.org/ThaddeusJiang/parcel-antd-template)
[![codecov](https://codecov.io/gh/ThaddeusJiang/parcel-antd-template/branch/master/graph/badge.svg)](https://codecov.io/gh/ThaddeusJiang/parcel-antd-template)

a react spa template by parcel and antd.

## Feature
- Parcel
- Ant Design
- Test & CI
- Code Format


## Getting started
```
// Install
yarn

// Starts the development server.
yarn start

// Bundles the app into static files for production.
yarn build

// Starts the test runner.
yarn test
```

## File Structure
```
├── mock                     # 本地模拟数据
├── public
│   └── favicon.ico          # Favicon
│   ├── index.html           # HTML 入口模板
│   ├── manifest.json        # PWA
├── src
│   ├── assets               # 本地静态资源
│   ├── components           # 业务通用组件
│   ├── layouts              # 通用布局
│   ├── models               # 数据模型
│   ├── routes               # 业务页面入口和常用模板
│   ├── services             # 后台接口服务
│   ├── utils                # 工具库
│   ├── index.js             # 应用入口
│   ├── index.less           # 全局样式
│   └── router.js            # 路由入口
├── tests                    # 测试工具
├── README.md
└── package.json
```