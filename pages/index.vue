<template>
  <c-box as="main" max-w="1320px" mx="auto" p="10">
    <c-heading>
      Stay near Austin’s top sights
    </c-heading>
    <c-flex :flex-dir="['column', 'column', 'column', 'row']" mt="4" pos="relative">
      <c-box :w="['full', 'full', 'full', '70%']">
        <c-box
          pt="62.5%"
          bg-size="contain"
          bg-pos="50% 50%"
          bg-repeat="no-repeat"
          d="block"
          pos="relative"
          bg-image="url('https://a0.muscache.com/im/pictures/c1b0abb6-4be8-4cc0-8643-deab7c4db2c3.jpg?aki_policy=large')"
          flex-shrink="0"
        />
      </c-box>
      <c-stack
        py="10"
        spacing="4"
        px="8"
        rounded="12px"
        shadow="lg"
        :position="['relative', 'relative', 'relative', 'absolute']"
        right="0"
        :top="[-48, -48, -48, '50%']"
        :transform="['translateY(0)', 'translateY(0)', 'translateY(0)', 'translateY(-50%)']"
        :left="[0, 0, 0, 'calc(60% - 10px)']"
        mx="auto"
        bg="white"
        :w="['90%', '90%', '90%','40%']"
        font-weight="light"
      >
        <c-heading as="h3">
          Texas Capitol
        </c-heading>
        <c-text>
          “The pink-granite building is the centerpiece of downtown Austin, perched on a hill at 12th Street and Congress Avenue. Free guided tours are held daily, starting in the South Foyer, but brochures are also available on the first floor for self-guided tours. The Texas Legislature meets every two years, so you’ll have to check the schedule if you want to see an actual session in progress.”
        </c-text>
        <c-flex align="center">
          <c-avatar src="https://a0.muscache.com/im/pictures/user/947ac725-a288-405c-9b1e-4c793e070bdb.jpg?aki_policy=profile_medium" name="Heena" />
          <c-box ml="5">
            <p v-chakra font-weight="bold" line-height="1">
              Heena
            </p>
            <p>Lives in Cedar park</p>
          </c-box>
        </c-flex>
      </c-stack>
    </c-flex>
  </c-box>
</template>
