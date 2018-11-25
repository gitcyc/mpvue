<template>
    <div>
        <i-icon type="video" size="28" color="#80848f" />
        <i-icon type="accessory" size="28" color="#80848f" />
        <i-icon type="activity" size="28" color="#80848f" />
        <i-icon type="barrage_fill" size="28" color="#80848f" />
        <i-icon type="close" size="28" color="#80848f" />
        <i-icon type="coordinates" size="28" color="#80848f" />
        <i-icon type="customerservice" size="28" color="#80848f" />
        <i-button>默认按钮</i-button>
        <i-button type="error" long="true">联通两边按钮</i-button>
        <i-button type="primary">Primary</i-button>
        <i-button type="ghost">Ghost</i-button>
        <i-button type="info">Info</i-button>
        <i-button type="success">Success</i-button>
        <i-button type="warning">Warning</i-button>
        <i-button type="error">Error</i-button>
        <i-button type="primary" size="large">大尺寸</i-button>
        <i-button type="primary" size="default">默认尺寸</i-button>
        <i-button type="primary" size="small">小尺寸</i-button>
        <i-button type="success" shape="circle" size="large">大尺寸</i-button>
        <i-button type="success" shape="circle">默认尺寸</i-button>
        <i-button type="success" shape="circle" size="small">小尺寸</i-button>
        <i-button type="primary" loading="true">加载中按钮</i-button>
        <i-button type="primary" disabled>禁用按钮</i-button>
        <i-alert>
            An info prompt
        </i-alert>
        <i-alert type="success">
            An success prompt
        </i-alert>
        <i-alert type="warning">
            An warning prompt
        </i-alert>
        <i-alert type="error">
            An error prompt
        </i-alert>
        <i-alert>
            An info prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
        <i-alert type="success">
            An success prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
        <i-alert type="warning">
            An warning prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
        <i-alert type="error">
            An error prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
        <i-alert show-icon>
            An info prompt
        </i-alert>
        <i-alert type="success" show-icon>
            An success prompt
        </i-alert>
        <i-alert type="warning" show-icon>
            An warning prompt
        </i-alert>
        <i-alert type="error" show-icon>
            An error prompt
        </i-alert>
        <i-alert show-icon desc>
            An info prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
        <i-alert type="success" show-icon desc>
            An success prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
        <i-alert type="warning" show-icon desc>
            An warning prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
        <i-alert type="error" show-icon desc>
            An error prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
        <i-alert closable bind:close="handleClick">
            An info prompt
        </i-alert>
        <i-alert type="success" show-icon desc closable bind:close="handleClick">
            An success prompt
            <view slot="desc">Content of prompt. Content of prompt.</view>
        </i-alert>
    </div>
</template>

<script>

</script>
