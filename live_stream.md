<div className="mb-2">
            <div className="text-lg font-bold text-blue-900">
              抖音直播内容流多玩法场景开发
            </div>
            <div className="flex flex-wrap items-baseline gap-x-4">
              <ul className="ml-4 pl-1 leading-tight space-y-1 list-disc">
                <li>
                  <b className="inline-block">业务背景：</b>
                  中台内容流以播放器形式嵌入网页端，承接抖音直播实时流与回放流服务，覆盖跟播、视频剪辑、审核等场景。
                  需支持视频/音频、多玩法与高并发实时互动，助力多业务平台低成本快速接入直播内容，保障运营管理效率与用户体验。
                </li>
                <li>
                  <b className="inline-block">我的职责：</b>
                  主导语音房、“你点我唱”等 8+互动玩法组件开发，结合实时监听与轮询机制，基于 IM 消息与 SEI
                  数据构建毫秒级 UI同步机制，支持直播间动态布局与麦位调整，封装直播/回放状态隔离Hook，多状态、高并发、多玩法场景下的组件开发与优化，保障高并发下的用户体验与系统稳定性。
                </li>
              </ul>
            </div>
          </div>
          <div>
            <div className="text-lg font-bold text-blue-900">
              抖音作者基础管理平台权限体系建设 & 搭建平台站点级权限链路优化：
            </div>
              <ul className="ml-4 pl-1 leading-tight space-y-1 list-disc">
                <li>
            主导构建用户-角色-资源RBAC权限链路机制，建立页面级访问控制体系，支持用户主动发起权限申请与后台自动审批生效，提升权限配置灵活性。
                   </li>
                   </ul>
</div>

<strong>直播间插件与动态玩法组件开发（多状态、高并发）：</strong>
<li>开发语音房、“你点我唱”、“电台付费连线”、“星愿瓶”等互动玩法组件，支持复杂联动与实时互动。</li>
<li>实现Banner插件、礼物特效、用户卡片、PK玩法等组件的状态同步与布局切换，提升玩法复用与系统可维护性。</li>

<strong>多消息来源整合与直播/回放状态隔离：</strong>
<ul>
  <li>封装IM消息订阅Hook，实时监听用户状态、礼物、弹幕等事件，毫秒级UI状态同步，替代高频轮询。</li>
  <li>监听SEI视频流数据（如ui_layout、grids），驱动麦位视图与布局实时更新。</li>
  <li>设计IM消息+SEI数据优先、接口为辅的数据更新机制，实现高并发场景下的实时性与性能优化。</li>
  <li>封装直播/回放状态隔离Hooks，直播用IM实时监听，回放用接口轮询，优化代码结构与逻辑清晰度。</li>
</ul>

<li>
                  <b className="inline-block">技术实现：</b>
                  <ul className="ml-4 list-[circle] leading-tight space-y-1">
                    <li>
                      <b className="inline-block">
                        直播间插件与动态玩法组件开发（多状态、高并发）：
                      </b>
<ul className="ml-4 list-[circle]">
                        <li>
                          主导语音房、“你点我唱”等 8+
                          互动玩法组件开发，支持多用户实时互动与复杂玩法联动，组件复用率提升至
                          85%。
                        </li>
                        <li>
                          封装统一状态管理与高复用组件，优化 UI
                          状态同步机制（延迟缩短至 100ms），玩法接入效率提升
                          60%，保障高并发下的用户体验。
                        </li>
                      </ul>
                    </li>

 <li>
                      <b className="inline-block">
                        多消息来源整合与直播/回放状态隔离：
                      </b>
                      <ul className="ml-4 list-[circle]">
                        <li>
                          基于 IM 消息与 SEI 数据构建毫秒级 UI
                          同步机制，支持直播间动态布局与麦位调整，接口调用频率降低
                          70%，状态刷新延迟控制在 80ms 以内。
                        </li>
                        <li>
                          封装直播/回放状态隔离
                          Hook，结合实时监听与轮询机制，提升代码清晰度与可维护性，保障高并发场景下系统稳定性。
                        </li>
                      </ul>
                    </li>
                  </ul>
</li>

