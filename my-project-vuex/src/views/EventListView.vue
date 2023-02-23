<template>
  <div class="events">
    <EventCard v-for="event in events" :key="event.id" :event="event" />
  </div>
</template>

<script>
import EventCard from '@/components/EventCard.vue'

export default {
  name: 'EventList',
  components: {
    EventCard,
  },
  data() {
    return {
      events: [
        {
          id: 123456,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline at this event',
          location: 'Tehran',
          date: 'November 28, 2022',
          time: '12:00',
          petsAllowed: true,
          organizer: 'Kat Laydee',
        },
        {
          id: 123456,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline at this event',
          location: 'Tehran',
          date: 'November 28, 2022',
          time: '12:00',
          petsAllowed: true,
          organizer: 'Kat Laydee',
        },
        {
          id: 123456,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline at this event',
          location: 'Tehran',
          date: 'November 28, 2022',
          time: '12:00',
          petsAllowed: true,
          organizer: 'Kat Laydee',
        },
        {
          id: 123456,
          category: 'animal welfare',
          title: 'Cat Adoption Day',
          description: 'Find your new feline at this event',
          location: 'Tehran',
          date: 'November 28, 2022',
          time: '12:00',
          petsAllowed: true,
          organizer: 'Kat Laydee',
        },
      ],
    }
  },
}
</script>

<style scoped>
.events {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
